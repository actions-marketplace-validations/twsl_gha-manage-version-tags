# Github Actions Manage Version Tags

Creates or updates shorter version tags based on a full semantic version tag

```yml
  - name: Manage short version tags
    uses: twsl/gha-manage-version-tags@v1
    with:
      token: ${{ secrets.GITHUB_TOKEN }}
```
