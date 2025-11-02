# Configuration

This directory contains configuration files for different environments and purposes.

## Structure

### Environments (`environments/`)
Environment-specific configuration files:
- `development.json` - Development environment settings
- `staging.json` - Staging environment settings
- `production.json` - Production environment settings
- `test.json` - Testing environment settings

### Schemas (`schemas/`)
Configuration schemas and validation rules:
- JSON schemas for configuration validation
- Environment variable schemas
- API request/response schemas

### Templates (`templates/`)
Configuration file templates:
- Email templates
- Document templates
- Report templates
- Notification templates

## Configuration Guidelines

1. **Never commit sensitive data** - Use environment variables for secrets
2. **Use environment-specific files** - Keep configs separate per environment
3. **Document all settings** - Add comments explaining configuration options
4. **Validate configurations** - Use schemas to validate config files
5. **Use defaults wisely** - Provide sensible defaults where appropriate

## Environment Variables

Create a `.env` file in the root directory with:
```
DATABASE_URL=
API_KEY=
JWT_SECRET=
SMTP_HOST=
SMTP_PORT=
```

See `.env.example` for a complete list of required variables.
