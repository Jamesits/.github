# .github

## Badges

![Works - On My Machine](https://img.shields.io/badge/Works-On_My_Machine-2ea44f)

Project Status series:

- ![Project Status - Development](https://img.shields.io/badge/Project_Status-Development-red)
- ![Project Status - Premature](https://img.shields.io/badge/Project_Status-Premature-yellow)
- ![Project Status - Feature Complete](https://img.shields.io/badge/Project_Status-Feature_Complete-2ea44f)
- ![Project Status - Abandoned](https://img.shields.io/badge/Project_Status-Abandoned-lightgrey)

## Mend Renovate Configuration

### Define Packages Manually in Comments

```plaintext
# renovate: datasource=xxx [depName=xxx] packageName=xxx/yyy [versioning=xxx]
some_version = "1.2.3"

# or

# renovate: datasource=xxx [depName=xxx] packageName=xxx/yyy [versioning=xxx]
"1.2.3"
```
