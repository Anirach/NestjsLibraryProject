# NestjsLibraryProject
book-management/
├── src/
│   ├── books/
│   │   ├── books.controller.ts          # The main controller for book routes (API endpoints)
│   │   ├── books.service.ts             # Service for handling business logic, typically calling DatabaseService
│   │   └── models/
│   │       └── book.model.ts            # TypeScript model for the Book entity
│   ├── database/
│   │   └── database.service.ts          # Service for SQLite database connection and queries
│   ├── app.module.ts                    # The root module for the application
│   └── main.ts                          # Entry point of the NestJS application
├── database.sqlite                      # SQLite database file
├── package.json                         # Node.js package dependencies
├── nest-cli.json                        # NestJS CLI configuration
├── tsconfig.json                        # TypeScript configuration
└── README.md                            # Project documentation
