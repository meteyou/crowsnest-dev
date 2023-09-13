<!-- THIS FILE IS UPDATED AUTOMATICALLY, ANY CHANGES WILL BE OVERRIDDEN -->
# Changelog
All notable changes to Mainsail will be documented in this file.

## [3.0.7](https://github.com/mainsail-crew/mainsail/releases/tag/v3.0.7) - 2023-09-13
### Features

- **install**: Set gpu_mem on rpi devices | [2bbe265](2bbe265e83ce0c2afeb07478e6d1c96d8ebfceda)
- **logging**: Extend error trace in logging | [4124e65](4124e65ec44885654d3cdafae66efc0d5010632f)

### Bug Fixes and Improvements

- **hwhandler.sh**: Fix error in device logging | [b0c011b](b0c011b4ef9aea19352b90cab7d06383eef555eb)
- **hwhandler.sh**: Fix error in device logging (#169) | [5333a62](5333a624982e3c29a93c1342c2b9aebba1de68cd)
- **hwhandler.sh**: Fix error in device logging (#169) (#170) | [c9bc304](c9bc30414e10e0fadf20e379b614b28869783c22)
- **install**: Wrong syntax in config.txt | [5e95c0d](5e95c0d3bdc9c2b1361b0fd8b5ba9227eb8c3fdd)
- **install**: Fixes error in unattended mode | [efe4dfd](efe4dfd189cc4bdb757ace0f5e03b1af43d1ebdf)
- Ensure device is raspberry if os is buster | [05a971b](05a971b259e994021dfe3d46e33c46f7d2e74b22)
- Fix error introduced by crudini | [722c7ca](722c7ca3f8b2ae336282abe4a09b6fae11dddb21)
- Disable SC2317 | [e214673](e21467358e09242de7e4f0826d2268c2e6f5e936)
- Store log_level in var instead in function | [9a66358](9a663584433bec74059ce7b205ecdcb32efa27f7)
- Fix add_update_entry condition | [a5a36e5](a5a36e5c3d153f0b568ea731b7e3b02badb139f4)
- Disable debug output in make config | [48ab81a](48ab81a4370fa04beccc0358ea60a7a27fab6a1d)
- Fix startup error on ubuntu arm | [0c49dc7](0c49dc796f8cc7ea9d0d8a9b6cb70f13713dee52)
- Fix raspicam detection | [2a4fbd9](2a4fbd9c77459c408c0ce2fe0eb06a3c11058779)
- Fix error causing cam list to fail | [e3bd2e2](e3bd2e2e57a4961a1af436bbeeed6c9aa901156b)
- Fix error not exiting script on error | [42ce0ba](42ce0ba29784781549bea6cb67bec105d5dbe8b5)
- Fix error exit on failure | [a07e42a](a07e42a1acf27d55eaa6b977a9b0c248e2cf13bd)
- Fix func detect_libcamera | [0c524b7](0c524b725df2b6b99f45cf64d683410d8120d62e)
- Fix error in ustreamer.sh | [3081093](308109323a76b9dbf8b7150e886e10b0e9cfd948)
- Fix wrong gpumem calculation (#176) | [e9f36c9](e9f36c9c2603931d1a35dcb33fb034543f1089a0)
- Fix wrong syntax in gpumem (#177) | [dacc0d9](dacc0d9d3a97454101a4d553ac229731446666fe)

### Refactor

- Refactor install chain | [4444ea5](4444ea58fdff64f531ecb406d34c9bc3e7962b42)
- Remove unnecessary ffmpeg version check | [f8ce308](f8ce308fa514cb47098ba33376de46caa2ac58d9)
- Refactor hwhandler.sh | [6c1aec1](6c1aec18b471910457c0196a5ba7c3de8c821871)

### Documentation

- **readme**: Refactor readme.md | [09f4cb1](09f4cb1ed2dc7c015da2fa97fad2f7e7220e118d)
- Improve README.md, add FAQ section | [5954969](595496941c152b88163bf86a58b9324b58848d82)
- Improve readme, add link to config section | [3bc6d7d](3bc6d7dd105959d6a0e1c4d6cfea30b68297befa)
- Fix typo in readme.md | [f945da3](f945da33e8768ba73424319d78b579bb842954c6)
- Add keyword cam note | [142e4de](142e4de4eebeda5ff088f17c45f2b6044fb6a296)
- Add warning not to change log_path | [b112300](b112300cedef41a27e219c293ba6c9b1593a7ca9)
- Improve linebreaks | [b7035a9](b7035a9207e80c1530d0a2cd6efa8b9b172078fd)
- Improve spelling | [96949b7](96949b7d754b1c3659567c09394d88e4b30ace62)
- Add link to discord | [3c1ec15](3c1ec157580f8c537b10bec57254db7ea22d1d06)
- Enhanced faq error 127 | [90a6901](90a6901bfef3fec120cb5454fa39ee58f00660c7)
- Enhanced faq for raspicam issues | [33981e7](33981e763cd8f9e710d2cce40bea3526b22f4ec3)
- Updated documentation for device definition (#65) | [dc27e3f](dc27e3f52aa16c49f089adc3076b5e67ac578136)
- Updated Readme.md | [7d207e6](7d207e6d84c4ebabc43eb1cadc678e62260f2b04)
- Changed layout | [ad081e6](ad081e67d67a209cd2601af94bf9d18da452b980)
- Fixed typo | [b6e2de2](b6e2de2c25963a35e6685ae681bfc858e1d4292b)
- Improves layout | [04f29cb](04f29cbb98be346ac402159637a18c6255a03274)
- Fix typo | [bb38f36](bb38f36cb06f8a0f5760600c00ebcef48e1dedb4)
- Fix typo | [00fe721](00fe721bf352350a92c9d450789dd0e1ba17d55e)
- Fix typo and rework layout (#80) | [5418550](541855054f6de4dfa8ff4d5e73dd36b213049903)
- Update Readme.md | [f6b841e](f6b841e92f5e0e6e8d275177ac4a7da51b8555a9)
- Add camera-streamer to README.md | [f8c78c5](f8c78c570ce0def6f1f8b6a2f11ecc8c29a212fd)
- Change test formation | [4c4e232](4c4e232ee55a60016ac4fe54be5cd549eeee0b5a)
- Removed TODO.md | [1df3f43](1df3f4377a5752b23a57d2ce5b7f247d7ed7b8d9)
- Fix clarity of backend packages (#108) | [4f69c94](4f69c9476fcec7e94559ac8603d090150c801742)

### Other

- Add not-on-github bot (#68) | [d044786](d04478635bb83d2b8b3e7bffaa48bafa98b413b1)
- Add v4l2ctl logging prefix | [43b86a3](43b86a33d7c95465fcd05acadef7ecf823042811)
- Add error message if v4l2-ctl errors out | [20ed6a8](20ed6a8b585a92e8a0e7d8333e81b6e8ca7044e1)
- Add TODO.md | [f458974](f45897447f03433a7d3c7217e1c4c72ead3dd146)
- Update TODO.md | [42cd77d](42cd77dc968260de605297786043ea3bd6b34c15)
- Update TODO.md | [9d6c46e](9d6c46e2f86df689c2a9709e2b90f927f1875210)
- Update TODO.md | [f065b29](f065b2952f443f16463967b0fda0c771a3202790)
- Allow backend names as mode | [3a1a929](3a1a9294ad88f1f1f830e61c9f7bee0a841e81bc)
- Add note to crowsnest.conf | [952dac9](952dac98a13564be34d1bbce68383273ff905d63)
- Update conf and readme to new params | [745631a](745631aed0124dab97faceab9b03f460f1f358e8)
- Add release.yml workflow | [8889d57](8889d5776f38e8392ec9a79d5430d5445c7bdc31)
- Test release workflow | [af187f6](af187f6c42c2cf7fb4d43082d729b9883e08ba64)
- Fix release workflow | [5657dce](5657dce1009066626dec10ffd86c0287accdf0d7)

## [3.0.6](https://github.com/mainsail-crew/mainsail/releases/tag/v3.0.6) - 2022-11-24
### Bug Fixes and Improvements

- Fixes missing legacy cam stack in ubuntu | [607bdda](607bdda902c0eebd0660865ec01509bc2fcb44aa)
- Fixes install error on Linux Mint | [0e11271](0e112711c74ccea82ddfb85538bbe0fc1f80d665)
- Add new parameter for rtsp-simple-server | [c6dd973](c6dd973d331699935b76665120febf824601635f)

### Documentation

- Add Ubuntu 22.04 - RPI as tested | [b8bed93](b8bed93f289ab98a4680e1f96d05d9158f53a22e)
- Add Linux Mint as tested ditribution | [2cbe951](2cbe9515b00a4d6504e92afc82412a59f27be027)

### Other

- Refactor log output of rtsp-simple-server | [957207b](957207b44874a5c5faa76fed157197590b9dc43f)

## [3.0.5](https://github.com/mainsail-crew/mainsail/releases/tag/v3.0.5) - 2022-11-24
### Other

- Bump rtsp-simple-server to v0.20.2 | [53b4d52](53b4d52f935c1cfd7faf75cf19c28a75c6f13ce4)

## [3.0.4](https://github.com/mainsail-crew/mainsail/releases/tag/v3.0.4) - 2022-11-24
### Features

- **install**: Adds ubuntu armv7l support | [ee59a12](ee59a12d59cb2db173a93b266c4766b853bd0364)
- Add no_proxy parameter | [8fe1100](8fe11005e183e12042e52f2d90dc7a8472e37415)

### Bug Fixes and Improvements

- Fixes error in ustreamer install | [046641a](046641af045c98ada6eb0c450c8e694765f3677a)
- Fix error in install.sh | [e2b4cd8](e2b4cd8cd2e65cab8857f1662b5b831b5cdfaad6)
- Error in func create_filestructure | [0eb04cf](0eb04cf2a6ba4a9b2eff29a1cb8e0817059f723b)
- Fix syntax error in dev-helper.sh | [df8a696](df8a6962ef634d03de254f1358be2a2b9378c7cc)
- Fixes wrong path to crowsnest-rtsp.yml | [cffea68](cffea681af1f3d1700ed56f97bd97b2628d59c0a)

### Refactor

- Implements new install mechanism | [d4a2c08](d4a2c08152766b40df151d3a1bee75e3aeafa7bf)

### Documentation

- Updated README.md | [f7ec29f](f7ec29f2f14927e8ea6434f2fc69f8c991d2ddc6)
- Added ubuntu server 20.04 as tested and working (#59) | [f7cf226](f7cf2260f28901f33f5bc979778afeade8129c10)

### Other

- Changes install routine | [d407c68](d407c683c0d05488e830acf982ff9908cca8ef6a)
- Update readme.md of custompios module | [77f23e0](77f23e01b2a942e3281ed975a67a5f7a010d7e23)

## [3.0.3](https://github.com/mainsail-crew/mainsail/releases/tag/v3.0.3) - 2022-09-04
### Bug Fixes and Improvements

- **ustreamer.sh**: Fixes duplicate format setting | [aab54f8](aab54f8ab29e79e4fa9acf2af234cbe2bbbb1f8c)
- Fixes blocky view after reboot | [dabb66c](dabb66c992e0981d3c26d9bd7e8853236145c552)

## [3.0.2](https://github.com/mainsail-crew/mainsail/releases/tag/v3.0.2) - 2022-09-04
### Bug Fixes and Improvements

- **messages**: Deprecated message shows wrong name | [e268090](e2680909ab08a3512e0e0974c857e795e55fe4ee)
- Fixes typo in install.sh | [946fad1](946fad1fd6f70fac92bd074203f4b085c4e89954)

### Refactor

- Refactor of User input during install | [8df5078](8df5078b3d6db6b49b6aaaaa77805006149e01c9)

## [3.0.1](https://github.com/mainsail-crew/mainsail/releases/tag/v3.0.1) - 2022-08-12
### Features

- Switch logo according to light or dark mode | [a5a5df8](a5a5df806967efbfb0950283a0c2771e74d124a8)
- Allow mjpeg as valid parameter | [ffba103](ffba10350b813dee24b238000ad45f13a75ea390)

### Bug Fixes and Improvements

- **install**: Fixes error in removing webcamd | [5a9c245](5a9c24593ad6483819568018088f611dab0c16ee)
- **make build**: Clone ustreamer if not present | [f726bda](f726bda796bd5f3aad4f9c4ae0046333bc2866ab)
- **uninstall**: Fixes error service not disabled. | [3c4e4f8](3c4e4f8098dc09318ba0e10a0762765545ce6431)
- Fixes install error if config.txt missing | [1af5d9c](1af5d9c46f44c326b357bbf7ac1fb8ae0466656a)
- Fixes install error on ubuntu aarch64 | [9d9f07b](9d9f07b5f9f0e027a88feb670accdbf1cf37232d)
- Used wrong condition | [7af4ee8](7af4ee85d372e63b5289583d39085bc06de2385c)
- Libjpeg62-turbo has no install target | [3a5f65b](3a5f65b018263210efc529ccd1955ef36753e933)
- Fixes error patching moonraker.conf | [4b2532d](4b2532d495654a7969e51cd47511575e2d4474f0)
- Fixes error in brokenfokus function | [3df7fed](3df7fedb4d38d2ce830c9a891abd987a36a8829f)
- Fix error using installer on armbian | [a3fba61](a3fba6105f0b8d825469f1c46ecd7fbde2bb4c35)
- Used wrong terminology for diskspace | [2fb45c3](2fb45c3283b2b7563f66c23b6342e43eaeea441a)

### Documentation

- Rename webcam.conf to crowsnest.conf in readme.md (#21) | [d8ef492](d8ef49226a0140ba04f6b680145e23fc9916a81c)

## [3.0.0](https://github.com/mainsail-crew/mainsail/releases/tag/v3.0.0) - 2022-06-16
### Features

- **install**: Add unattended mode to installer | [c4d4795](c4d4795089d78bd7727a30f3ef608bf426345cca)
- **logging**: Display host information in log file | [687be54](687be54de1ca5c7c5aa566c8becb8e3ff707c5e6)

### Bug Fixes and Improvements

- **install**: Fix error using custopizer unattended | [3a48d47](3a48d47f5ae041664064c1ce0bfcd3d7bb608041)
- **install**: Fixes error that leads to unusable moonraker.conf | [fab3772](fab3772e1074b1689d6919bff59cb4d05b1a0649)
- **logging**: Fixes error in log output of host information | [b6055ce](b6055cecff115ea6d239754abc3936dc4dfe1364)
- **v4l2ctl**: Fixes error in broken_focus detection | [e42799b](e42799bac636da3cb989fbf3849e0eeaa02dcf42)
- Fixes uncomplete log if using bullseye | [b8a7046](b8a7046db8d8ae3d97944c07aa50a9ffedf0fa69)

### Refactor

- **install**: Improve install if unattended | [dcb5581](dcb55816d3c4edab04e2dcab3a0d4590bba5eb10)
- **installl**: Refactor install chain | [6071c6f](6071c6fc769dbda8ab18aa16e46fdcba28d8288c)
- **logging**: Strips out comments in func print_cfg | [5b8c072](5b8c072db3bacc2346d3e340d9ce8499c4639782)
- Improve detection of chroot jail | [36893bf](36893bf9d4fd9f3de61689cba8d6230b12dd8e82)
- Refactor installer and custompios module | [ee6598c](ee6598c2927bc337571d3d589af27a1b75333c8a)

### Other

- **docs**: Updates readme to latest changes. | [c52cf40](c52cf40a962657854ce55564f506fcec5bbd7619)
- **docs**: Update discord url | [fac3667](fac3667b0fe0214d10b132bc705fb8f6187b49d0)
- **install**: Remove backup if unattended | [dc710d0](dc710d0abe07d2b5e6c5385535d61ecd833455d2)
- **rtsp**: Update rtsp-simple-server to latest release | [18ab214](18ab214d490de08304280c1f2b250c8a9a746fcb)
- **rtsp**: Update rtsp config template | [1117287](11172878eb4395040e44544228700e0020ecc25c)

## [2.4.0](https://github.com/mainsail-crew/mainsail/releases/tag/v2.4.0) - 2022-04-10
### Features

- Add debug logging for v4l2_control | [2e3cf93](2e3cf935686b95315bac260f28ba9b816dc2c830)
- Added feature versioncontrol | [6f17019](6f17019fb83ea0228018259bd390fd7fb1fd2a43)

### Bug Fixes and Improvements

- Fixes focus_absolute not correct after streamer started | [3bfea5a](3bfea5ad19d24d2d73cc63cf286c39aafadc2065)
- Fixes logging empty value if not set or available | [3692b31](3692b310a5734f223280af5b2600c331e14c3a33)

### Refactor

- Refactored logging.sh | [7c5188a](7c5188a7e0af9410eeaf2e8ec2d6a51c3fa2e42f)

### Other

- Enabled inherited ERR Trap | [3c52447](3c52447822668bae39591cd8b0882fa84b9acaf2)

## [2.2.0](https://github.com/mainsail-crew/mainsail/releases/tag/v2.2.0) - 2022-04-02
### Features

- Log available v4l2 controls | [03d03f8](03d03f851e9201c7813ce3d41fde2931bc317206)

## [2.1.0](https://github.com/mainsail-crew/mainsail/releases/tag/v2.1.0) - 2022-03-26
### Features

- Enable detection of csi adaptors | [664d9b5](664d9b539b5d6e9c017cfd416911d0ef5f0e9ac6)

## [2.0.1](https://github.com/mainsail-crew/mainsail/releases/tag/v2.0.1) - 2022-03-07
### Bug Fixes and Improvements

- **build**: Fix aarch64 error at rtsp-simple-server install | [d8e98ac](d8e98acd6a1427ac19cab96cca5cd079661e7fa8)
- **build**: Fix typo in sed command | [96f6592](96f6592e5c20ecb2dd17d71b9ab22b75857f232f)
- **hwhandler.sh**: Fixed correct detection of Hardware | [c60cf2f](c60cf2fd492ad0464080ed2c4280877844ead3d4)
- **messages**: Used wrong modes in log. | [b2aedb6](b2aedb678376463b18e2c706134c750d426f6088)
- **messages**: Typo in deprecated_msg_1 | [67c32d9](67c32d95f4b91efac1d2ab5b2ffff060934d80d9)
- **update**: Fixes error in func copy_logrotate | [1aa3103](1aa310341fbd88a503c6bf78ac5aaa6d81b158d6)
- **update**: Version of apps were not checked nor updated | [605cc4f](605cc4f5d56ee58b8f03b7e756fe27b84108e1c3)
- **update**: Version of apps were not checked nor updated | [d378318](d378318ebe149c109dc9777617b62a33e9fb0742)
- **update**: Wrong path used for file templates | [bb6ed2f](bb6ed2f41704d80a934632958e22a71bb62a2f9c)
- **updater**: Critical typo in func copy_logrotate | [62ee73b](62ee73b6da1792d6d125a6acd2ddb0bbde217d3d)
- Refactored install.sh and update.sh | [8a5fcb0](8a5fcb08268c71628f1d5a4653393f6d63b3ebe6)
- Fixed custompios module | [afcb651](afcb651abd501a715345100e79f5a4a2c61515eb)

### Refactor

- Refactored custompios module | [0176ce7](0176ce769ca38748a3c9037c8d348ba529a7590c)

### Documentation

- Fixed error in README.md | [93ce6a2](93ce6a298f271c15f3c95fa387378a3116e02b58)

### Other

- **update**: Removed message if RTSPtoWebRTC is not installed | [4170a25](4170a25b640fe03ba1fe0c0c1c4451d693023092)

