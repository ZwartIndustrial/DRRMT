# Upload DRRMT to GitHub

## 1. Create the repository

Open the pre-filled repository form:

https://github.com/new?owner=ZwartIndustrial&name=DRRMT&description=DR+Rene+Magic+Toolbox+installer+and+release+notes

Use these settings:

- Owner: `ZwartIndustrial`
- Repository name: `DRRMT`
- Description: `DR Rene Magic Toolbox installer and release notes`
- Visibility: choose **Public** when customers must be able to download without signing in; otherwise choose **Private**.
- Do not add a generated README, `.gitignore`, or licence because these files are already supplied in this starter package.

Click **Create repository**.

## 2. Upload the repository files

On the new empty repository page, select **uploading an existing file**. Upload the contents of this starter folder, but do not upload the MSI itself to the normal repository history.

Commit message:

```text
Add DRRMT 2.0.2 release documentation
```

## 3. Create the MSI release

1. Open `https://github.com/ZwartIndustrial/DRRMT/releases`.
2. Click **Draft a new release**.
3. Choose **Create new tag** and enter `v2.0.2`.
4. Set the release title to `DR Rene Magic Toolbox 2.0.2`.
5. Copy the contents of `RELEASE_NOTES_2.0.2.md` into the release description.
6. Drag `DR_Rene_Magic_Toolbox_2.0.2.msi` into the release Assets area.
7. Select **Set as the latest release**.
8. Click **Publish release**.

## 4. Customer download links

Latest release page:

https://github.com/ZwartIndustrial/DRRMT/releases/latest

Version 2.0.2 direct download:

https://github.com/ZwartIndustrial/DRRMT/releases/download/v2.0.2/DR_Rene_Magic_Toolbox_2.0.2.msi

## Future versions

For each new version:

1. Update `CHANGELOG.md`.
2. Commit the changelog change.
3. Create a new tag such as `v2.0.3`.
4. Create a GitHub Release for that tag.
5. Upload the newly built MSI as the Release asset.
