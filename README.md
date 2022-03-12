# Nest.js-todo-api

This api has below function

## UserStory

- User can add a task.
- User can show a list of tasks.
- User can delete a task.
- User can edit a task.

## Structure

```bash
.
├── .eslintrc.js
├── .gitignore
├── .prettierrc
├── README.md
├── nest-cli.json
├── package.json
├── src
│   ├── app.module.ts
│   ├── config
│   │   └── typeorm-config.service.ts
│   ├── main.ts
│   └── tasks
│       ├── dto
│       │   └── task-property.dto.ts
│       ├── pipe
│       │   └── task-status.pipe.ts
│       ├── task.entity.ts
│       ├── tasks.controller.ts
│       ├── tasks.module.ts
│       ├── tasks.service.spec.ts
│       └── tasks.service.ts
├── test
│   ├── app.e2e-spec.ts
│   └── jest-e2e.json
├── tsconfig.build.json
├── tsconfig.json
└── yarn.lock

6 directories, 21 files
```

## Using of language, framework, technology

- Node.js
- Nest.js
- TypeScript
- PostgreSQL
- TypeORM
- SwaggerUI

## Requirement

- "@nestjs/common": "^8.0.0"
- "@nestjs/config": "^1.1.6"
- "@nestjs/core": "^8.0.0"
- "@nestjs/platform-express": "^8.0.0"
- "@nestjs/swagger": "^5.2.0"
- "@nestjs/typeorm": "^8.0.3"
- "class-transformer": "^0.5.1"
- "class-validator": "^0.13.2"
- "pg": "^8.7.3"
- "reflect-metadata": "^0.1.13"
- "rimraf": "^3.0.2"
- "rxjs": "^7.2.0"
- "swagger-ui-express": "^4.3.0"
- "typeorm": "^0.2.41"

## Usage

```bash
git clone https://github.com/hinatha/Nest.js-todo-api
cd Nest.js-todo-api
yarn
yarn start:dev
```

## Future plans

- API development for SQL table design on Nest.js
