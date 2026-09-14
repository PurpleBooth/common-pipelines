# Changelog
All notable changes to this project will be documented in this file. See [conventional commits](https://www.conventionalcommits.org/) for commit guidelines.

- - -
## v0.16.7 - 2026-09-14
#### Bug Fixes
- (**ci**) pin Homebrew/actions/setup-homebrew to main SHA - (a9eefe0) - Billie
#### Continuous Integration
- Remove cache-to directive from Docker build workflow - (1d3ce15) - Billie Thompson
- Update Docker workflow cache and remove unused outputs - (07c4440) - Billie Thompson
- Enable registry-based cache in docker-build workflow - (403d255) - Billie Thompson (aider)
- Update clippy command to use stable toolchain - (204fbf8) - Billie Thompson
- add conditional execution for cargo build on Windows - (0246b52) - Billie Thompson
- Add shell and name to cargo initialization step - (f62b0aa) - Billie Thompson
- Specify shell as bash in rust-check workflow - (66e05e2) - Billie Thompson
- Add cargo build step if Cargo.lock is missing in rust-check.yml - (da4366d) - Billie Thompson
- Rename cargo install step to cargo build in rust-check.yml - (87e16af) - Billie Thompson
- Switch to nightly rust toolchain in workflow - (31d670d) - Billie Thompson
- Update rust toolchain to nightly in workflow - (0164de3) - Billie Thompson
- Switch to nightly rust toolchain in CI workflow - (e2d7c35) - Billie Thompson
- Add cargo build step if Cargo.lock is missing - (e8196a7) - Billie Thompson
- add name to cargo install step in rust-check workflow - (4eb112f) - Billie Thompson
- Add cargo install step if Cargo.lock is missing - (3b5eb5f) - Billie Thompson
- Simplify clippy command in GitHub workflow - (82c4e88) - Billie Thompson
- Switch from nightly to stable Rust toolchain in workflows - (a532697) - Billie Thompson
- Switch rust toolchain from nightly to stable in workflow - (00ea6a5) - Billie Thompson
#### Miscellaneous Chores
- (**deps**) update purplebooth/generate-formula-action action to v0.1.16 - (ea6900d) - renovate[bot]
- (**deps**) update actions/attest-build-provenance action to v2.3.0 - (242c13a) - renovate[bot]
- (**deps**) update docker/setup-buildx-action action to v3.10.0 - (1714a84) - renovate[bot]
- (**deps**) update docker/build-push-action action to v6.16.0 - (e545800) - renovate[bot]
- (**deps**) update docker/setup-qemu-action action to v3.6.0 - (f3f84a8) - renovate[bot]
- (**deps**) update docker/bake-action action to v6 - (93b0293) - renovate[bot]
- (**deps**) update ncipollo/release-action action to v1.16.0 - (3e5b646) - renovate[bot]
- (**deps**) update specdown/setup-specdown-action action to v0.2.32 - (aa7848f) - renovate[bot]
- (**deps**) update docker/metadata-action action to v5.7.0 - (0e082ca) - renovate[bot]
- (**deps**) update taiki-e/install-action digest to 83254c5 - (f9ea925) - renovate[bot]
- (**deps**) update actions/attest-build-provenance digest to db473fd (#253) - (d7364e5) - renovate[bot], *renovate[bot]*
- (**deps**) update taiki-e/install-action digest to ab3728c (#252) - (e9f0e93) - renovate[bot], *renovate[bot]*
- (**deps**) update taiki-e/install-action digest to 09dc018 (#251) - (241d707) - renovate[bot], *renovate[bot]*
- (**deps**) update armakuni/github-actions action to v0.19.6 (#246) - (e7b259a) - renovate[bot], *renovate[bot]*
- (**deps**) update taiki-e/install-action digest to f1390fd (#250) - (d93c68c) - renovate[bot], *renovate[bot]*
- (**deps**) update actions/cache action to v4.2.3 (#244) - (95e6837) - renovate[bot], *renovate[bot]*
- (**deps**) update taiki-e/install-action digest to 2c41309 (#248) - (dcaab45) - renovate[bot], *renovate[bot]*
- (**deps**) update actions/attest-build-provenance digest to c074443 (#247) - (867651f) - renovate[bot], *renovate[bot]*
- (**deps**) update taiki-e/install-action digest to 3c8fc6e (#245) - (90fab3b) - renovate[bot], *renovate[bot]*
- (**deps**) update taiki-e/install-action digest to e032365 (#243) - (427a143) - renovate[bot], *renovate[bot]*
- (**deps**) update taiki-e/install-action digest to ad09049 (#242) - (8852b2f) - renovate[bot], *renovate[bot]*
- (**deps**) update taiki-e/install-action digest to 5ae641a (#239) - (1837c93) - renovate[bot], *renovate[bot]*
- (**deps**) update armakuni/github-actions action to v0.19.5 (#237) - (eb9f687) - renovate[bot], *renovate[bot]*
- (**deps**) update actions/attest-build-provenance digest to 520d128 (#241) - (889ad7f) - renovate[bot], *renovate[bot]*
- (**deps**) update docker/bake-action digest to 4a9a8d4 (#240) - (cd9675f) - renovate[bot], *renovate[bot]*
- (**deps**) update taiki-e/install-action digest to a7adeb1 (#236) - (1a9af07) - renovate[bot], *renovate[bot]*
- (**deps**) update taiki-e/install-action digest to c87777c (#231) - (02c30e7) - renovate[bot], *renovate[bot]*
- (**deps**) update taiki-e/install-action digest to a86da1a (#230) - (fae1e7a) - renovate[bot], *renovate[bot]*
- (**deps**) update taiki-e/install-action digest to acd2589 (#229) - (1abe433) - renovate[bot], *renovate[bot]*
- (**deps**) update taiki-e/install-action digest to 8484225 (#228) - (745a178) - renovate[bot], *renovate[bot]*
- (**deps**) update taiki-e/install-action digest to 03381f5 - (daf04d0) - renovate[bot]
- (**deps**) update actions/attest-build-provenance digest to 7668571 (#224) - (7a64427) - renovate[bot], *renovate[bot]*
- (**deps**) update taiki-e/install-action digest to acf70b3 (#223) - (6fc8fd7) - renovate[bot], *renovate[bot]*
- (**deps**) update actions/attest-build-provenance action to v2.0.1 (#222) - (108a511) - renovate[bot], *renovate[bot]*
- (**deps**) update actions/attest-build-provenance digest to c4fbc64 (#221) - (71df6c0) - renovate[bot], *renovate[bot]*
- (**deps**) update actions/cache action to v4.2.0 (#220) - (a3c3658) - renovate[bot], *renovate[bot]*
- (**deps**) update taiki-e/install-action digest to f635080 (#219) - (d5b7325) - renovate[bot], *renovate[bot]*
- (**deps**) update taiki-e/install-action digest to 6aa8b42 (#217) - (6a8d3a7) - renovate[bot], *renovate[bot]*
- (**deps**) update actions/attest-build-provenance action to v2 (#218) - (1aff531) - renovate[bot], *renovate[bot]*
- (**deps**) update docker/bake-action digest to 3fc70e1 (#216) - (7e36f29) - renovate[bot], *renovate[bot]*
- (**deps**) update taiki-e/install-action digest to c4bf614 (#215) - (55a2466) - renovate[bot], *renovate[bot]*
- (**deps**) update taiki-e/install-action digest to ec9269c (#214) - (3dabf33) - renovate[bot], *renovate[bot]*
- (**deps**) update docker/build-push-action action to v6.10.0 (#213) - (2eed9b2) - renovate[bot], *renovate[bot]*
- (**deps**) update taiki-e/install-action digest to 6da51af (#212) - (97128c4) - renovate[bot], *renovate[bot]*
- (**deps**) update taiki-e/install-action digest to 33e32f5 (#211) - (ee99fd1) - renovate[bot], *renovate[bot]*
- (**deps**) update docker/metadata-action action to v5.6.1 (#210) - (81b3298) - renovate[bot], *renovate[bot]*
- (**deps**) update taiki-e/install-action digest to 5d427d8 (#209) - (44de302) - renovate[bot], *renovate[bot]*
- (**deps**) update taiki-e/install-action digest to 85c1f06 (#208) - (52af516) - renovate[bot], *renovate[bot]*
- (**deps**) update taiki-e/install-action digest to 9c04113 (#207) - (6357219) - renovate[bot], *renovate[bot]*
- (**deps**) update taiki-e/install-action digest to c6dc131 (#206) - (5e826cc) - renovate[bot], *renovate[bot]*
- (**deps**) update actions/attest-build-provenance action to v1.4.4 (#205) - (f4adc79) - renovate[bot], *renovate[bot]*
- (**deps**) update taiki-e/install-action digest to 959f8ad - (e8db093) - renovate[bot]
- (**deps**) update taiki-e/install-action digest to 678b06b - (fde8e2d) - renovate[bot]
- update Cargo.toml edition and keywords - (13ae5de) - Billie Thompson
- Update Rust edition in Cargo.toml from 2018 to 2021 - (e455e3f) - Billie Thompson (aider)

- - -

## v0.16.6 - 2024-11-02
#### Bug Fixes
- Add key - (1fb914b) - Billie Thompson

- - -

## v0.16.5 - 2024-11-02
#### Bug Fixes
- Remove default for secrets - (4f0aad3) - Billie Thompson
- secrets to be passed via secrets - (818d8c2) - Billie Thompson
- Add options for gpg - (f317cb1) - Billie Thompson

- - -

## v0.16.3 - 2024-11-01
#### Bug Fixes
- correct hash list - (e06eb33) - Billie Thompson

- - -

## v0.16.2 - 2024-11-01
#### Bug Fixes
- Apply to all bins - (ac8e7d8) - Billie Thompson

- - -

## v0.16.1 - 2024-11-01
#### Bug Fixes
- Set the bins version - (11ea4ea) - Billie Thompson
#### Continuous Integration
- make the names of the steps better - (06941ff) - Billie Thompson
- Correct bins - (f92ec8d) - Billie Thompson

- - -

## v0.16.0 - 2024-11-01
#### Features
- add release action using bake - (4325c13) - Billie Thompson
#### Miscellaneous Chores
- make the name a little nicer in a ci step - (40748ae) - Billie Thompson

- - -

## v0.15.1 - 2024-10-31
#### Bug Fixes
- Add bins to the bake - (8ad260c) - Billie Thompson
#### Miscellaneous Chores
- add target and .idea to the ignores - (c547282) - Billie Thompson

- - -

## v0.15.0 - 2024-10-31
#### Continuous Integration
- remove latest from edge - (44707e9) - Billie Thompson
#### Features
- Build bins from bake too - (c3595e4) - Billie Thompson
#### Miscellaneous Chores
- **(deps)** update taiki-e/install-action digest to a533731 - (9ce6772) - renovate[bot]
- **(deps)** update actions/checkout action to v4.2.2 - (340d263) - renovate[bot]
- **(deps)** update actions/cache action to v4.1.2 - (886f5b3) - renovate[bot]
- **(deps)** update taiki-e/install-action digest to 939f4af - (d0d3ca4) - renovate[bot]
- **(deps)** update taiki-e/install-action digest to 42f4ec8 - (714a13e) - renovate[bot]
- **(deps)** update taiki-e/install-action digest to 5ffe29a - (4690f8c) - renovate[bot]
- **(deps)** update actions/cache action to v4.1.1 - (ba251e4) - renovate[bot]
- **(deps)** update actions/checkout action to v4.2.1 - (96f6b22) - renovate[bot]
- **(deps)** update actions/cache action to v4.1.0 - (ee38b3e) - renovate[bot]
- **(deps)** update docker/setup-buildx-action action to v3.7.1 - (3e6f5d1) - renovate[bot]
- **(deps)** update docker/bake-action digest to 2e3d19b - (2a9180d) - renovate[bot]
- **(deps)** update docker/build-push-action action to v6.9.0 - (9a1ffca) - renovate[bot]
- **(deps)** update docker/bake-action digest to 64673bc - (cda35ea) - renovate[bot]
- **(deps)** update taiki-e/install-action digest to 9bef7e9 - (2c18bdc) - renovate[bot]
- **(deps)** update docker/build-push-action action to v6.8.0 - (f81621a) - renovate[bot]
- **(deps)** update docker/bake-action digest to e626c73 - (750dc7e) - renovate[bot]
- **(deps)** update actions/checkout action to v4.2.0 - (0c6e27e) - renovate[bot]
- **(deps)** update rustsec/audit-check action to v2 - (0d29bf8) - renovate[bot]
- **(deps)** update taiki-e/install-action digest to 7348990 - (56774cc) - renovate[bot]

- - -

## v0.14.1 - 2024-09-20
#### Bug Fixes
- Do nottt - (bc3d087) - Billie Thompson
#### Continuous Integration
- syn - (d1851b7) - Billie Thompson
- Add docker args version to bake-push - (0f07110) - Billie Thompson
- Update bake-build.yaml - (a8751f8) - Billie Thompson
- Update bake-build.yaml - (8be6045) - Billie Thompson
- Change meta - (4df5784) - Billie Thompson
- Change meta - (580eeb4) - Billie Thompson
- meta-without-version - (b4fbaf5) - Billie Thompson
- Tags - (67bd605) - Billie Thompson
- correct setttttt - (7118fb9) - Billie Thompson
- Correct cache - (9eccef6) - Billie Thompson
- correct cache - (67ecb33) - Billie Thompson
- correct ref - (539f06c) - Billie Thompson
- Correct import - (fe047dd) - Billie Thompson
- Make cache array - (01d6453) - Billie Thompson
- Caching - (a52cb7a) - Billie Thompson
- Correct cache - (95fa297) - Billie Thompson
- cache - (017c353) - Billie Thompson
- Cache - (6729337) - Billie Thompson
- remove tags - (346ab5a) - Billie Thompson
- Remove unused tags - (270810e) - Billie Thompson
#### Miscellaneous Chores
- **(deps)** update taiki-e/install-action digest to 0241d8f - (98510f6) - renovate[bot]
- **(deps)** update taiki-e/install-action digest to 35aa409 - (0c9fb0c) - renovate[bot]
- **(deps)** update specdown/setup-specdown-action action to v0.2.30 - (328739f) - renovate[bot]
- **(deps)** update taiki-e/install-action digest to da8fe73 - (705ee41) - renovate[bot]
- **(deps)** update armakuni/github-actions action to v0.19.4 - (1c7bfcb) - renovate[bot]
- **(deps)** update actions/attest-build-provenance action to v1.4.3 - (dc63ae7) - renovate[bot]
- **(deps)** update taiki-e/install-action digest to e51c197 - (7bc5290) - renovate[bot]
- **(deps)** update taiki-e/install-action digest to f3e9a65 - (6a9f734) - renovate[bot]
- **(deps)** update docker/bake-action action to v5 - (ba17e20) - renovate[bot]

- - -

## v0.14.0 - 2024-09-03
#### Bug Fixes
- Remove error - (5fefa1f) - Billie Thompson
- Remove syn - (d47f032) - Billie Thompson
- Correct syn - (dbd1232) - Billie Thompson
- Remove push - (1caa657) - Billie Thompson
#### Features
- Add bake push - (eb43015) - Billie Thompson
- Add bake build - (970b517) - Billie Thompson

- - -

## v0.13.0 - 2024-09-03
#### Continuous Integration
- Remove load - (45d02dd) - Billie Thompson
#### Features
- Add a bake step - (b4005c0) - Billie Thompson
#### Miscellaneous Chores
- **(deps)** update taiki-e/install-action digest to f2b65a3 - (6087a7e) - renovate[bot]
- **(deps)** update purplebooth/changelog-action action to v0.3.4 - (38d7999) - renovate[bot]
- **(deps)** update taiki-e/install-action digest to 1105389 - (ea0b56f) - renovate[bot]
- More utility tags - (7e298cf) - Billie Thompson

- - -

## v0.12.6 - 2024-08-29
#### Bug Fixes
- use oci ouput - (6e39920) - Billie Thompson

- - -

## v0.12.5 - 2024-08-29
#### Bug Fixes
- Cache docker image build - (561d72b) - Billie Thompson

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