# Update Enterprise CMS

Checks and updates the version of the CMS on a Enterprise repository

## Usage

```yaml

- name: Update Client CMS
    uses: clockwork-marketing-uk/actions-update-enterprise-cms@1.0.0
    with:
     github-token: ${{ secrets.GITHUB_TOKEN }}
     github-user: ${{ github.actor }}
     fa-npm-token: ${{ secrets.FA_NPM_TOKEN }}
     npm_token: ${{ secrets.NPM_TOKEN }}
     gh_package_key: ${{ secrets.GH_PACKAGE_KEY }}

```
