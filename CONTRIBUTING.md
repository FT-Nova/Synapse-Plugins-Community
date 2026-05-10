# Contributing to SYNAPSE Community Plugins

Thank you for contributing to the SYNAPSE plugin ecosystem!

## Contribution Process

1. **Fork the repository**
2. **Create your plugin** in the appropriate category
3. **Test thoroughly**
4. **Submit pull request**
5. **Community review**

## Plugin Structure

```
plugins/category/your-plugin/
├── README.md           # Plugin documentation
├── plugin.yaml         # Plugin metadata
├── src/               # Plugin source code
├── tests/             # Plugin tests
├── LICENSE            # License file
└── CHANGELOG.md       # Version history
```

## Quality Standards

### Code Quality

- ✅ Follow language conventions
- ✅ Include type hints/annotations
- ✅ Add docstrings/comments
- ✅ No hardcoded secrets

### Testing

- ✅ >80% test coverage
- ✅ Unit tests
- ✅ Integration tests
- ✅ CI/CD pipeline

### Documentation

- ✅ Clear README with examples
- ✅ Parameter descriptions
- ✅ Usage examples
- ✅ Troubleshooting section

### Security

- ✅ Sanitize user input
- ✅ Use secure defaults
- ✅ Declare all permissions
- ✅ No hardcoded credentials

## Categories

Choose the appropriate category:

- `ai-tools/` - AI and ML integrations
- `data/` - Data processing
- `devops/` - Development tools
- `integrations/` - Third-party services
- `productivity/` - Productivity tools
- `security/` - Security tools
- `utilities/` - General utilities

## Review Process

1. **Automated checks**: CI/CD tests run automatically
2. **Community review**: Community members review code
3. **Core team approval**: Required for sensitive permissions
4. **Merge**: Once approved, plugin is merged

## Getting Help

- **Discord**: Join the SYNAPSE community server
- **Discussions**: https://github.com/FTMahringer/Synapse/discussions
- **Documentation**: https://ftmahringer.github.io/Synapse/docs/plugins/development/getting-started

## Code of Conduct

Be respectful and professional. Follow the [SYNAPSE Code of Conduct](https://github.com/FTMahringer/Synapse/blob/main/CODE_OF_CONDUCT.md).

## License

By contributing, you agree to license your plugin under an OSI-approved license (MIT, Apache 2.0, or GPL).
