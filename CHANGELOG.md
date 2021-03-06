Changelog
=========

### 2.0.1 (14/12/2014)

- Improving the clarity of the terminal output generated by `django_node.npm.install`.

### 2.0.0 (12/12/2014)

- API change for `django_node.npm.install`
- Extra arguments are now accepted as `*args`, rather than as a tuple. `silent` must now be an explicit keyword argument.

### 1.0.0 (12/12/2014)

- Removed the `RAISE_ON_MISSING_DEPENDENCIES` and `RAISE_ON_OUTDATED_DEPENDENCIES` settings.

### 0.2.0 (7/12/2014)

- Most of the functions are now exposed from `django_node.node` and `django_node.npm`.
- The Node.js API is now composed of...
  - `django_node.node.is_installed`
  - `django_node.node.version`
  - `django_node.node.version_raw`
  - `django_node.node.run`
  - `django_node.node.ensure_installed`
  - `django_node.node.ensure_version_gte`
- The NPM API is now composed of...
  - `django_node.npm.is_installed`
  - `django_node.npm.version`
  - `django_node.npm.version_raw`
  - `django_node.npm.run`
  - `django_node.npm.ensure_installed`
  - `django_node.npm.ensure_version_gte`
  - `django_node.npm.install`


### 0.1.0 (3/12/2014)

- Initial release
