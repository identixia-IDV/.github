# Publishing and discoverability

## Publish the organization profile

1. Create or open the **public** repository `identixia-IDV/.github`.
2. Upload the contents of this directory to its default branch, using `main` for shared policy links. Do not upload the enclosing `repositories` directory.
3. Confirm `profile/README.md` exists. Logo and brand mark images load directly from the public `identixia-IDV/identixia-assets` repository on `main`; confirm both images are accessible. If the `.github` branch is not `main`, update shared policy links accordingly.
4. Open the organization's Overview page while signed out. Check the logo, tables, calls to action, and platform links on desktop and mobile.
5. Verify each linked product repository is public and contains a usable release or sample. Remove links to unpublished products until they are ready.

GitHub displays `profile/README.md` on the organization overview. The root README explains this repository. See [GitHub's organization profile documentation](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile).

Default community files apply where a repository has no corresponding local file. Repositories with their own issue templates or template configuration override the entire default issue-template set. See [GitHub's default community files documentation](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file).

## Suggested organization settings

Set these in GitHub; adding this document does not change account settings.

- **Display name:** Identixia | Identity Verification & Biometric AI
- **Description:** Face recognition, liveness detection, ID document OCR, and self-hosted identity verification SDKs for mobile, desktop, and server applications.
- **Website:** https://identixia.com
- **Public email:** contact@identixia.com
- **Avatar:** use `identixia-assets/brand/mark.png`. GitHub controls its browser favicon; a profile README cannot replace it.
- **.github repository description:** Identixia identity verification and biometric AI: product guides, SDK integrations, documentation, and support.
- **.github repository website:** https://identixia.com

## Suggested pinned repositories

Pin public, maintained repositories with complete setup instructions, demos, and downloadable runtimes. A balanced six-repository starting selection is:

1. `FaceRecognition-LivenessDetection-Android`
2. `FaceRecognition-LivenessDetection-iOS`
3. `FaceRecognition-LivenessDetection-Docker`
4. `FaceLivenessDetection-Docker`
5. `ID-Document-Recognition-Liveness-Detection-Docker`
6. `ID-Document-Recognition-Liveness-Detection-Flutter`

Review this selection as customer demand and published products change.

## Repository descriptions and topics

Use accurate, specific descriptions on each product repository. Suggested patterns:

| Product | Description pattern | Relevant topics |
| --- | --- | --- |
| Combined face SDK | Face recognition and passive liveness detection for PLATFORM. Identixia SDK sample for biometric identity verification. | `face-recognition`, `face-verification`, `liveness-detection`, `biometrics` |
| Face liveness | Passive face liveness and deepfake detection for PLATFORM. Identixia anti-spoofing SDK and integration sample. | `liveness-detection`, `anti-spoofing`, `deepfake-detection`, `presentation-attack-detection` |
| Document SDK | ID document OCR and authenticity checks for PLATFORM. Identixia passport, identity card, MRZ, and barcode integration sample. | `document-verification`, `document-recognition`, `ocr`, `mrz`, `identity-verification` |
| IDV platform | Self-hosted identity verification with document and selfie capture, verification sessions, reviews, and webhook integration. | `identity-verification`, `kyc`, `self-hosted`, `digital-onboarding` |

Replace PLATFORM with the actual target. Add applicable platform topics such as `android`, `ios`, `flutter`, `react-native`, or `docker`, and the brand topic `identixia`. Only use topics and capability claims that match the repository's actual build.

## Search visibility and customer trust

The profile uses descriptive headings, readable product explanations, searchable capability names, and direct links. These help customers understand and discover the products; search rankings and indexing are not guaranteed. GitHub controls the page's HTML metadata, so this README is not a place to add SEO meta tags or structured-data scripts.

- Keep the organization name, website, and contact details consistent across GitHub and the company website.
- Link to the organization from the company website and documentation.
- Keep meaningful product text in Markdown, rather than only inside images.
- Maintain useful READMEs, real samples, release notes, and relevant topics in each public product repository.
- Publish benchmark or certification claims only with a public report that identifies the evaluated product and version. This profile intentionally makes no unverified accuracy, certification, customer-count, or pricing claims.
- Review links, runtime availability, supported platforms, and contact details with each product release.

## Content provenance and link review

Product copy is based on this workspace's product READMEs and GitBook sources, especially `guides/choose-a-product.md`, `documentation/idv/README.md`, and the face liveness Docker sample. Contact details come from the shared documentation contact include. Brand images reference `identixia-assets/brand/logo.png` and `identixia-assets/brand/mark.png` directly; no duplicate brand assets are stored here. Decorative icons use the Lucide set through Iconify, matching the existing product README convention. Icons have empty alt text because adjacent text supplies their meaning; the profile remains readable if the icon service is unavailable.

Product repository names were checked against local customer repository folders. Public availability of the organization, website, and all deep links must still be checked at publication; the web lookup during preparation could not retrieve the organization or company homepage.

