# NPM dependency `bin` precedence bug

This is a sandbox for testing NPM dependency binary resolution.

Consumer 1 & 2 are packages that both depend on both Dependency 1 & 2, which both attempt to register the to `conflicting-command`.
