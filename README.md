# Project Name: FlagtickGroup

## Overview

Brief project modules.

## Project Structure

### Laravel Backend
```plaintext
├── app
│   ├── Http
│   │   └── Controllers
│   │       └── Api
│   │           └── V1
│   │               └── RoleController.php
│   ├── Model
│   │   └── Role.php
│   └── Repositories
│       └── Role
│           ├── RoleRepository.php
│           └── EloquentRole.php

### Vue Frontend
├── resources
│   └── assets
│       └── js
│           ├── components
│           │   └── Role.vue
│           ├── modal
│           │   └── role
│           │       ├── UpdateModal.vue
│           │       └── NewModal.vue
│           └── datatable
│               └── role
│                   ├── Column.vue
│                   └── Manipulation.vue
