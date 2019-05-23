# Release Notes

## [v4.1.39](https://github.com/cnvs/canvas/compare/v4.1.38...v4.1.39)

### Fixed
- Fixed Moment.js not respecting the app timezone ([#474](https://github.com/cnvs/canvas/issues/474), [#482](https://github.com/cnvs/canvas/pull/482), [a9c64d9](https://github.com/cnvs/canvas/commit/a9c64d965e4acad7f0e65432118cef9cd82f44a8))

## [v4.1.38](https://github.com/cnvs/canvas/compare/v4.1.37...v4.1.38)

### Changed
- Refactored `PostTags` to `PostsTags` ([f091d32](https://github.com/cnvs/canvas/commit/f091d322430c27b2b29c8356bc68cde532b1eff1))

### Added
- Added support for a weekly digest e-mail ([7d385bd](https://github.com/cnvs/canvas/commit/7d385bd9da3a4a37ded04373c67203f35f531f19))
- Added multilingual support for Russian ([418ad29](https://github.com/cnvs/canvas/commit/418ad290637cef92a8d561c0471af28f468c8e7b))

## [v4.1.37](https://github.com/cnvs/canvas/compare/v4.1.36...v4.1.37)

### Changed
- Minor updates to the sponsorship page ([91a6ff5](https://github.com/cnvs/canvas/commit/91a6ff598821fe76627398be6b725c2ad3cb522c))

## [v4.1.36](https://github.com/cnvs/canvas/compare/v4.1.35...v4.1.36)

### Added
- Added sponsor information ([6476549](https://github.com/cnvs/canvas/commit/64765492e228ac859399054f7aee05e5fcf07b33))

## [v4.1.35](https://github.com/cnvs/canvas/compare/v4.1.34...v4.1.35)

### Changed
- Refactored list components and updated prop definitions ([092a0cb](https://github.com/cnvs/canvas/commit/092a0cb085111ef307b3f74302182f4e684a374c), [11f43c0](https://github.com/cnvs/canvas/commit/11f43c0cb07c3162077bcb28a7bf81ee35bf0ae1))

## [v4.1.34](https://github.com/cnvs/canvas/compare/v4.1.33...v4.1.34)

### Changed
- Refactored Vue components to better align with the official style guide ([6c27729](https://github.com/cnvs/canvas/commit/6c2772926320e25a7f550d7da427772526465df2), [4fbc257](https://github.com/cnvs/canvas/commit/4fbc257c249538d6c7b52ddbf04af08b6d2735b1))

## [v4.1.33](https://github.com/cnvs/canvas/compare/v4.1.32...v4.1.33)

### Changed
- Refactored the blade templates [2d37762](https://github.com/cnvs/canvas/commit/2d377623bbf103d593b326008e898e8f969a31a4)
- Updated the default template dependencies [8136282](https://github.com/cnvs/canvas/commit/8136282391830d73c38afc12c487e37f10a2a7ca)

## [v4.1.32](https://github.com/cnvs/canvas/compare/v4.1.31...v4.1.32)

### Changed
- Updated the French translations ([#466](https://github.com/cnvs/canvas/commit/7ff9a356d5cccac6dee735a4915e81b89482c71f), [#467](https://github.com/cnvs/canvas/commit/f7c1ed69d1058d1d608757b2e0eb936e8e941cb5), [#468](https://github.com/cnvs/canvas/commit/ff5d2b7b5c45f5b86dd816694bba0fe74e8337d4), [#469](https://github.com/cnvs/canvas/commit/9e46ab3f1683ff587a77be19a2f5c3b871aff57e), [#470](https://github.com/cnvs/canvas/commit/c25df9f1336cf3bfe687815877351315ffc0c5ed))

### Added
- Added the ability to remove a featured image ([10b0019](https://github.com/cnvs/canvas/commit/10b0019f61b7a5d3ff22843fd0ef250ffab689c0))

### Fixed
- Fixed the missing featured image caption translation ([c5f26b4](https://github.com/cnvs/canvas/commit/c5f26b4721a1de27d60d9f4e6bb39230fd3f767f))

## [v4.1.31](https://github.com/cnvs/canvas/compare/v4.1.30...v4.1.31)

### Changed
- Refactored the MediaController into a single action for simplicity ([2201769](https://github.com/cnvs/canvas/commit/22017691233fabfcea16cb473ca64e1573dd751c))
- Refactored the `i18n` objects into single translation endpoints throughout the components for better maintainability ([0af8873](https://github.com/cnvs/canvas/commit/0af8873a90e26cf97ca9aec11c67f8851a11b36e))

## [v4.1.30](https://github.com/cnvs/canvas/compare/v4.1.29...v4.1.30)

### Fixed
- Fixed the query scope for published posts ([be072bd](https://github.com/cnvs/canvas/commit/be072bd583e738ed7422cb31a171b73e4f8d5e2f))

## [v4.1.29](https://github.com/cnvs/canvas/compare/v4.1.28...v4.1.29)

### Added
- Added multilingual support for French, Portuguese and Chinese (Simplified) ([#447](https://github.com/cnvs/canvas/issues/447), [f622b1e](https://github.com/cnvs/canvas/commit/f622b1e4864ecd1a526c79a467dda7b1aa1485ad))

## [v4.1.28](https://github.com/cnvs/canvas/compare/v4.1.27...v4.1.28)

### Changed
- Added a `v-cloak` directive to the main editor component ([5d81ea4](https://github.com/cnvs/canvas/commit/5d81ea49d3d67b193274ff9b038344bb884d69f9))

## [v4.1.27](https://github.com/cnvs/canvas/compare/v4.1.26...v4.1.27)

### Changed
- Refactored resource handling from the `register()` to the `boot()` method in the service provider ([#462](https://github.com/cnvs/canvas/pull/462)) 

## [v4.1.26](https://github.com/cnvs/canvas/compare/v4.1.25...v4.1.26)

### Added
- Added a PostTags model ([0942a5b](https://github.com/cnvs/canvas/commit/0942a5b0b03b96e9ab1981fed18038fe8e7a9686))

### Fixed
- Skipped the `canvas:install` test ([#456](https://github.com/cnvs/canvas/issues/456), [53f21e6](https://github.com/cnvs/canvas/commit/53f21e67a8e1f004249b1bf21b2786b06ebeec99))

## [v4.1.25](https://github.com/cnvs/canvas/compare/v4.1.24...v4.1.25)

### Added
- Added a unit test for precision number formatting ([8398356](https://github.com/cnvs/canvas/commit/8398356b819ce27d98895658277e0a6897613464))

## [v4.1.24](https://github.com/cnvs/canvas/compare/v4.1.23...v4.1.24)

### Changed
- Changed the `laravel/framework` requirement to `illuminate/support` ([#453](https://github.com/cnvs/canvas/pull/453), [a1306c5](https://github.com/cnvs/canvas/commit/a1306c5c925f6357f6c150c4249e44505ce15c57), [b056182](https://github.com/cnvs/canvas/commit/b056182da87cc92403672cbf81f062a5ea72c171))
- Updated Unsplash links to open in new tabs ([2fe5658](https://github.com/cnvs/canvas/commit/2fe5658c363afea9b03ad270353f9659bab19494))
- Refactored the `storage_path` configuration to less explicit with images ([b0ab792](https://github.com/cnvs/canvas/commit/b0ab7926446d018461ca9a644a2ac571ad6eb046))

## [v4.1.23](https://github.com/cnvs/canvas/compare/v4.1.22...v4.1.23)

### Fixed
- Fixed the removal of all topics and tags from a post ([e83930f](https://github.com/cnvs/canvas/commit/e83930f7e6b62e70e8d66af3601f56dc21200e1a))

## [v4.1.22](https://github.com/cnvs/canvas/compare/v4.1.21...v4.1.22)

### Changed
- Updated the favicon to an .ico format ([08e8dc6](https://github.com/cnvs/canvas/commit/08e8dc6d6a6f52aeb0e4ae033caf7103761c32c1))

## [v4.1.21](https://github.com/cnvs/canvas/compare/v4.1.20...v4.1.21)

### Changed
- Refactored the float parsing on stat view counts ([ea53999](https://github.com/cnvs/canvas/commit/ea539996fde96c5caedbcaa4ae10ac1a5b3b12fe))

### Fixed
- Included the post body in the stats index endpoint to not break the read times ([111291f](https://github.com/cnvs/canvas/commit/111291fa20ee910474467cc03aabc03a232b1a30))

## [v4.1.20](https://github.com/cnvs/canvas/compare/v4.1.19...v4.1.20)

### Added
- Added dynamic pagination to Vue component filtered lists ([ec087a4](https://github.com/cnvs/canvas/commit/ec087a4fcea738775df95df2d795e695b12d6b1d))

## [v4.1.19](https://github.com/cnvs/canvas/compare/v4.1.18...v4.1.19)

### Changed
- Removed unnecessary eager loading from the post index route ([09d01c6](https://github.com/cnvs/canvas/commit/09d01c622f04997dc23ae64ac9719a067a28b734))

### Added
- Added unit tests for the ViewThrottle middleware ([087832e](https://github.com/cnvs/canvas/commit/087832eb6b7439dbe0f9214fea99020e9eaeed39))

### Fixed
- Refactored the ViewThrottle middleware to prune posts from the session instead of simply filtering ([087832e](https://github.com/cnvs/canvas/commit/087832eb6b7439dbe0f9214fea99020e9eaeed39))

## [v4.1.18](https://github.com/cnvs/canvas/compare/v4.1.17...v4.1.18)

### Changed
- Removed the unnecessary auth check ([4e36d8c](https://github.com/cnvs/canvas/commit/4e36d8ca28939b06c3cbf23345b7c74eeae8fe6a))
- Version bump for dependencies ([fa661ea](https://github.com/cnvs/canvas/commit/fa661eafce842bcd78caf95b80fd1911ce912e05), [2c1feeb](https://github.com/cnvs/canvas/commit/2c1feeb282e1cbd319e3d8f096f052cf679ec255))

## [v4.1.17](https://github.com/cnvs/canvas/compare/v4.1.16...v4.1.17)

### Changed
- Minor branding updates ([6321678](https://github.com/cnvs/canvas/commit/63216782a497a1dc4434a806eaef100e8cac0255))

## [v4.1.16](https://github.com/cnvs/canvas/compare/v4.1.15...v4.1.16)

### Changed
- Updated the `Model::all()` usages to reduce the query sizes ([6655ecb](https://github.com/cnvs/canvas/commit/6655ecb78123e1a179c8514d85e02f9aa5d77c87), [0df1ba5](https://github.com/cnvs/canvas/commit/0df1ba52b8a972fcdc6d01f78c0af2c0a5c72c54))
- Refactored model attributes to use snake case ([d2f4784](https://github.com/cnvs/canvas/commit/d2f47840d75386f496ea9ff81a9baeb44841dd4c))
- Updated the Font Awesome library to 5.8 ([47af5b8](https://github.com/cnvs/canvas/commit/47af5b8bf11f3d62d7a189a6fc9bfb201a9fdac4))
- Updated the dark mode contrast ratios for increased readability ([a718b1b](https://github.com/cnvs/canvas/commit/a718b1bfa13223a9e73d233d336340978ea84f68))

### Added
- Added unit tests for the StoreViewData listener ([2e3aeb5](https://github.com/cnvs/canvas/commit/2e3aeb518aee9141fdec6485ca2c3844a7f98d24))
- Added unit tests for the Publish command ([637dd3f](https://github.com/cnvs/canvas/commit/637dd3fb2b1a1efd6a2c67fbeb77038737e8d725))

### Fixed
- Fixed the missing validation messages on Topics/Tags ([4d4231b](https://github.com/cnvs/canvas/commit/4d4231bd7da898e7ee28c38864944ede281cbb8d))

## [v4.1.15](https://github.com/cnvs/canvas/compare/v4.1.14...v4.1.15)

### Added
- Added a dark mode ([e3723ac](https://github.com/cnvs/canvas/commit/e3723ac6523ef000b0901f3c073a94bcad7cfebf))

## [v4.1.14](https://github.com/cnvs/canvas/compare/v4.1.13...v4.1.14)

### Fixed
- Fixed a plurality bug in the line chart components ([dc366f1](https://github.com/cnvs/canvas/commit/dc366f117c7b765d35a352bd996722f0745e17b1))
- Fixed the percentage calculations with popular reading time stats ([6222eb](https://github.com/cnvs/canvas/commit/6222ebb38654ca0c0ec17ee881977a027a6d72a0))

## [v4.1.13](https://github.com/cnvs/canvas/compare/v4.1.12...v4.1.13)

### Changed
- Refactored the test suite to be more concise and accurate ([573b6e8](https://github.com/cnvs/canvas/commit/573b6e877933fc4e0d2ef46a0686650304b5a9f8))
- Refactored the migrations into a root `database` directory ([573b6e8](https://github.com/cnvs/canvas/commit/573b6e877933fc4e0d2ef46a0686650304b5a9f8))
- Updated the `.gitignore` ([a83978b](https://github.com/cnvs/canvas/commit/a83978b63fe2d1e4b25551cd9bf81a3f9ecbb908))

### Added
- Added unit tests for the number suffix helper ([61d5b15](https://github.com/cnvs/canvas/commit/61d5b15eaee6bdf9571e5687cca9f80d4e309fe3))
