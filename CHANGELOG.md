0.5.6.0
=======

* Allow passing client side hashed passwords for signup and restore.

0.5.5.0
=======

* Allow passing client side hashed password to signin endpoint.

0.5.4.0
=======

* Bump versions for `lts-12.9`.

0.5.3.0
=======

* Support `servant-0.13`.

0.5.2.0
=======

* Support `servant-0.12`.

0.5.1.0
=======

* Versions bounds are relaxed.

0.5.0.0
=======

* Fix typo in `invalidatePermanentCodes`.
* Servant combinator.
* Rename migration function.

0.4.7.1
=======

* Relax `servant` and `servant-server` versions.

0.4.7.0
=======

* Make `withAuthToken` work properly.

0.4.6.0
=======

* Add `withAuthToken` to guard groups of endpoints.

0.4.5.0
=======

* Auto deriving `HasAuthConfig` and `HasStorage` for transformers.

0.4.4.1
=======

* `persistent-postgresql` is not actually used

0.4.4.0
=======

* Add `signinByHashUnsafe` for internal usage.

0.4.3.0
=======

* Implementation for `AuthFindUserByLogin` endpoint.
* Feature to manipulate with hashes of passwords. For instance, now you can store
hashed admin password in config.

0.4.2.0
=======

* Add implementation for `AuthCheckPermissionsMethod` and `AuthGetUserIdMethod` endpoints.

0.4.1.1
=======

* Relax `aeson` and `opt-parse-applicative` bounds.
* Add `monad-control` instances.

0.4.1.0
=======

* Remove persistent dependencies from abstract package.

0.4.0.0
=======

* Abstract over storage: persistent and acid-state backends.

0.3.2.0
=======

* Support lts-7.1 (ghc 8 and persistent-0.6)

0.3.0.0
=======

* Add authorisation by single usage codes.

0.2.0.1
=======

* Relax boundaries for ghc 8.0.1.

0.2.0.0
=======

* Implement `servant-auth-token-0.2.0.0` API.

0.1.2.0
=======

* Expose implementation of API for embedding in complex servers.

0.1.1.0
=======

* Added `restoreCodeGenerator` to configuration

0.1.0.0
=======

* Initial publication
