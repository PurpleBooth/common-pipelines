# Changelog
All notable changes to this project will be documented in this file. See [conventional commits](https://www.conventionalcommits.org/) for commit guidelines.

- - -
## v0.12.4 - 2024-08-29
#### Bug Fixes
- add arch and ver - (4e84c72) - Billie Thompson

- - -

## v0.12.3 - 2024-08-29
#### Bug Fixes
- add a cargo clean - (2827dd0) - Billie Thompson
#### Continuous Integration
- Add nfpm release supporttttttttt - (77f10a1) - Billie Thompson

- - -

## v0.12.2 - 2024-08-29
#### Bug Fixes
- Reduce spacing - (6883bec) - Billie Thompson
#### Continuous Integration
- Move hash generation to where it won't be overwritten - (596acf8) - Billie Thompson

- - -

## v0.12.1 - 2024-08-29
#### Bug Fixes
- Add annotaions - (138da9c) - Billie Thompson
#### Continuous Integration
- Remove md5s - (5d20202) - Billie Thompson

- - -

## v0.12.0 - 2024-08-29
#### Continuous Integration
- add correct rust check - (a5cbae6) - Billie Thompson
- change working directory nfpm - (73d745b) - Billie Thompson
- Add linter - (ca72569) - Billie Thompson
- add nfpm - (50f8aa2) - Billie Thompson
#### Features
- Move shas to notes - (74cbf9f) - Billie Thompson
#### Tests
- for shch - (0c8c9e0) - Billie Thompson

- - -

## v0.11.3 - 2024-08-26
#### Bug Fixes
- correct attestation to not include image name - (9afefa5) - Billie Thompson

- - -

## v0.11.2 - 2024-08-26
#### Bug Fixes
- Add prefix v back to tag - (e671c49) - Billie Thompson

- - -

## v0.11.1 - 2024-08-26
#### Bug Fixes
- Ignore push to docker registry - (2a15043) - Billie Thompson

- - -

## v0.11.0 - 2024-08-26
#### Continuous Integration
- add mutants terms - (68c414b) - Billie Thompson
#### Features
- Add a shell check option - (c5c8498) - Billie Thompson

- - -

## v0.10.1 - 2024-08-25
#### Bug Fixes
- minimise the amount of mutation testing - (9407d70) - Billie Thompson

- - -

## v0.10.0 - 2024-08-25
#### Features
- mutatuon testimg - (2f93800) - Billie Thompson

- - -

## v0.9.4 - 2024-08-24
#### Bug Fixes
- Try new docker authentication mechanism - (e2801ed) - Billie Thompson
#### Continuous Integration
- Remove duplicated build - (a1c46b3) - Billie Thompson

- - -

## v0.9.3 - 2024-08-24
#### Bug Fixes
- Use metadata for builds rather than generating the tags - (1cfea4c) - Billie Thompson
- Switch to metadata for generating tags - (36950b6) - Billie Thompson
#### Continuous Integration
- Change name of build and push step - (7e6270f) - Billie Thompson
#### Miscellaneous Chores
- **(deps)** update actions/cache action to v4.0.2 - (53787ec) - renovate[bot]

- - -

## v0.9.2 - 2024-08-21
#### Bug Fixes
- use the check reporter - (384975e) - Billie Thompson

- - -

## v0.9.1 - 2024-08-21
#### Bug Fixes
- Build on appropriate architectures - (937eaec) - Billie Thompson
- Default to amd and arm for docker images - (0daca32) - Billie Thompson
#### Continuous Integration
- Attest images and generate sbom - (2fc2d21) - Billie Thompson

- - -

## v0.9.0 - 2024-08-21
#### Continuous Integration
- We have switched to renovate - (6f4b18e) - Billie Thompson
#### Features
- Add sbom - (69b7a72) - Billie Thompson

- - -

## v0.8.30 - 2024-08-21
#### Bug Fixes
- **(deps)** bump PurpleBooth/generate-formula-action - (24416c6) - dependabot[bot]

- - -

## v0.8.29 - 2024-08-21
#### Bug Fixes
- Use new link checker - (db02d92) - Billie Thompson
#### Continuous Integration
- Allow merge groups - (3a0bce8) - Billie Thompson
- Allow merge groups - (f26ca43) - Billie Thompson
- Use changelog fro cog - (447bb30) - Billie Thompson
- correct env - (52c70cd) - Billie Thompson
- Use cog to generate the changelog - (9cf5310) - Billie Thompson

- - -

## v0.8.28 - 2024-08-14
#### Bug Fixes
- **(deps)** bump docker/build-push-action from 6.6.1 to 6.7.0 - (2d7dae7) - dependabot[bot]
#### Continuous Integration
- Add aarch64 target for mac - (b44f2b5) - Billie Thompson

- - -

## v0.8.27 - 2024-08-08
#### Bug Fixes
- **(deps)** bump docker/build-push-action from 6.5.0 to 6.6.1 - (3d098b0) - dependabot[bot]

- - -

## v0.8.26 - 2024-08-06
#### Bug Fixes
- Correct attestation - (7d43a78) - Billie Thompson
#### Continuous Integration
- Remove attestation for the git- tag as it fails - (5cd415d) - Billie Thompson
#### Miscellaneous Chores
- **(deps)** update actions/cache action to v4 - (6de0e83) - renovate[bot]

- - -

## v0.8.25 - 2024-08-02
#### Bug Fixes
- exclude the github directory - (b85fe11) - Billie Thompson

- - -

## v0.8.24 - 2024-08-02
#### Bug Fixes
- Add attestations for docker images - (b540d6a) - Billie Thompson
#### Continuous Integration
- Add renovate.json - (b60fa1d) - renovate[bot]

- - -

## v0.8.23 - 2024-08-01
#### Bug Fixes
- Give permisions to contents - (3d094d6) - Billie Thompson

- - -

## v0.8.22 - 2024-08-01
#### Bug Fixes
- Remove crc - (c006a37) - Billie Thompson

- - -

## v0.8.21 - 2024-08-01
#### Bug Fixes
- Remove stray colon - (c5599d1) - Billie Thompson

- - -

## v0.8.20 - 2024-08-01
#### Bug Fixes
- Use current action - (449c712) - Billie Thompson

- - -

## v0.8.19 - 2024-08-01
#### Bug Fixes
- add missing permision - (8ad3e9a) - Billie Thompson

- - -

## v0.8.18 - 2024-08-01
#### Bug Fixes
- Add attest - (8c0424b) - Billie Thompson

- - -

## v0.8.17 - 2024-08-01
#### Bug Fixes
- Correct version of upload artifact in action - (de59cdd) - Billie Thompson

- - -

## v0.8.16 - 2024-08-01
#### Bug Fixes
- only download bins not other artifacts - (3ce58fb) - Billie Thompson
#### Continuous Integration
- **(Mergify)** configuration update - (952a3b7) - Billie Thompson
- Ignore existing pr - (ec2ed8d) - Billie Thompson
- Force push over old homebrew formula on rerun - (94b34e8) - Billie Thompson

- - -

## v0.8.15 - 2024-08-01
#### Bug Fixes
- Switch to taiki-e - (5aa904a) - Billie Thompson

- - -

## v0.8.14 - 2024-08-01
#### Bug Fixes
- Add id-token for signing - (d040f06) - Billie Thompson

- - -

## v0.8.13 - 2024-08-01
#### Bug Fixes
- Add cosign - (b2374f4) - Billie Thompson

- - -

## v0.8.12 - 2024-08-01
#### Bug Fixes
- Add some hashes - (7ddfb22) - Billie Thompson

- - -

## v0.8.11 - 2024-08-01
#### Bug Fixes
- Group binaries into single directory - (aa54c91) - Billie Thompson

- - -

## v0.8.10 - 2024-07-31
#### Bug Fixes
- Use modern outupt format - (217a041) - Billie Thompson

- - -

## v0.8.9 - 2024-07-31
#### Bug Fixes
- Update artifact v4 - (2026702) - Billie Thompson

- - -

## v0.8.8 - 2024-07-31
#### Bug Fixes
- Ignore changelog - (e776d9c) - Billie Thompson

- - -

## v0.8.7 - 2024-07-31
#### Bug Fixes
- **(deps)** bump docker/setup-qemu-action from 2.2.0 to 3.2.0 - (419bb9c) - dependabot[bot]

- - -

## v0.8.6 - 2024-07-31
#### Bug Fixes
- **(deps)** bump ncipollo/release-action from 1.12.0 to 1.14.0 - (050a4ee) - dependabot[bot]

- - -

## v0.8.5 - 2024-07-31
#### Bug Fixes
- **(deps)** bump actions/download-artifact from 3 to 4 - (64beae9) - dependabot[bot]

- - -

## v0.8.4 - 2024-07-31
#### Bug Fixes
- **(deps)** bump docker/login-action from 2.2.0 to 3.3.0 - (01ce4ba) - dependabot[bot]
- **(deps)** bump docker/build-push-action from 4.1.1 to 6.5.0 - (de02a44) - dependabot[bot]
- **(deps)** bump actions/checkout from 4.1.3 to 4.1.7 - (96390a8) - dependabot[bot]

- - -

## v0.8.3 - 2024-07-31
#### Bug Fixes
- **(deps)** bump actions/upload-artifact from 3 to 4 - (9913582) - dependabot[bot]

- - -

## v0.8.2 - 2024-07-31
#### Bug Fixes
- **(deps)** bump docker/setup-buildx-action from 3.3.0 to 3.6.1 - (e8c150a) - dependabot[bot]

- - -

## v0.8.1 - 2024-07-30
#### Bug Fixes
- changelog argument formatting in release workflow - (5fe38b6) - Billie Thompson

- - -

## v0.8.0 - 2024-07-30
#### Bug Fixes
- Switch to binstall for installing just - (b04bf8c) - Billie Thompson
- Change the `cargo binstall cargo-edit` [...] - (b19cf39) - Billie Thompson
- Use binstall - (0865c57) - Billie Thompson
- Linting problems - (295806d) - Billie Thompson
- Add a cog file - (3dcc8cd) - Billie Thompson
- Only check from last tag - (551e45d) - Billie Thompson
#### Features
- switch to cog - (be94130) - Billie Thompson

- - -

Changelog generated by [cocogitto](https://github.com/cocogitto/cocogitto).