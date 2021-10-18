# Create Release Action

Tags a repository and creates a GitHub Release. This action performs the following steps:

* Calculate a new semantic version, based on the existing Git tags and commit messages.
* Tag the repository with the new version number.
* Generate a changelog containing all commits since the most recent release.
* Create a GitHub release with the calculated tag and changelog.

## Usage

```yaml
- uses: twin-digital/action-create-release@v1
```

## License

The contents of this repository are released under the [MIT License](LICENSE).
