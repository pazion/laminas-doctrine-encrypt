# Changelog

## 3.0.0
### Breaking changes
- Minimum version of PHP 8.1 required
- The required Laminas dependencies have been updated to newer versions

### Other
`EncryptionSubscriber.php`
If you use your own EncryptionSubscriber or extend from it:
All type declared values for the Doctrine manager have been changed from `ObjectManager $entityManager` to also support the EntityManager: `ObjectManager|EntityManager $entityManager` 
