# NgLaunchpad

## Installation

1. Clone the repository.
2. Run `npm install`.

## Recommended VS Code extensions

- Prettier
- Stylelint
- TSLint

## Development server

1. Run `npm start`.
2. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

- Take benefit of angular cli to generate required files.  
- Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Code linting

- Run `npm run lint` to check for linting errors and `npm run lint:fix` to try and fix them automatically.
- Alternatively you can use `npm run lint-css` and `npm run lint-css:fix` for focussing only on scss and html files.
- You won't be able to commit if there are lint errors in the code.

## Code Formatting

- We follow a particular set of rules as available in .tslint and .prettierrc
- Run `npm run fmt` to format the code automatically using recommended configuration of Prettier.
- Code automatically gets formatted with set rules during commit.

## Documenting components

- We use storybook for documenting our components and creating reusable components in isolation.
- Run `npm run storybook`.

## Running unit tests

- Run `npm run test` to execute the unit tests via Jest.
- Run `npm run test:coverage` to check unit tests coverage.
- Failing unit tests will not allow pushing code into the repository.

## Running end-to-end tests

1. Run `npm run e2e` to execute the end-to-end tests via Puppeteer.

## Build

1. Run `npm run build`.
2. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Deployment

1. CI-CD is in place to take care of automatic deployments.
2. There should not be any linting error or unit test failure for deployment to succeed.
3. Please check for deployment success tick before merging any pull requests.

## Further help, feedback, suggestion, whom should I contact

Raise an issue with appropriate details and we will look into it.
or contact `Ayush Sharma` via [email](mailto:hey.ayush.sharma@gmail.com)
