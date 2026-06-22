# TODO - member-manager

- [ ] Add Maven Wrapper files (`mvnw`, `mvnw.cmd`, `.mvn/`) to repo root (copy from a Quarkus starter ZIP) so `quarkus:dev` can run without system Maven.
- [ ] Re-run `.
  mvnw.cmd quarkus:dev` and capture startup output/errors.
- [ ] Implement Quarkus bootstrap:
  - [ ] Fill `AppStartup.java` with startup hook logic (currently empty).
  - [ ] Fill `SeedAdmin.java` so admin seeding works when enabled.
- [ ] Fix DB schema/migrations:
  - [ ] Populate `src/main/resources/db/migration/v1__init.sql` (currently empty) with required tables.
- [ ] Run `.
  mvnw.cmd test` to ensure unit/integration tests pass.

