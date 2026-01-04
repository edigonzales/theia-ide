```
yarn
yarn version --no-git-tag-version
yarn lerna version --exact --no-push --no-git-tag-version
git commit -a -m 'update to interlis-editor 0.0.XX'
git push
git tag v0.0.Y
git push origin v0.0.Y
```