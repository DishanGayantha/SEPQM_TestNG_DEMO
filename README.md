# TestNG User Auth Demo

Small, realistic Java + Maven project to demonstrate TestNG:

- Assertions
- Fixtures (`@BeforeMethod`, `@AfterMethod`)
- Mocking/Stubbing (Mockito)
- Test reports (TestNG `test-output/`)
- CI/CD (GitHub Actions workflow)

## Requirements

- Java 17+
- Maven 3.9+

## Run tests

```bash
mvn test
```

## Where to find reports

After `mvn test`:

- TestNG HTML reports: `test-output/index.html` and `test-output/emailable-report.html`
- (Optional) Surefire reports (may exist depending on runner): `target/surefire-reports/`

## Project layout

- Main code: `src/main/java/com/demo/auth/`
- Tests: `src/test/java/com/demo/auth/`
- TestNG suite: `src/test/resources/testng.xml`
- CI: `.github/workflows/ci.yml`
