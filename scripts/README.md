# Scripts

This directory contains utility scripts for various operational tasks.

## Structure

### Deployment (`deployment/`)
Scripts for deploying the application:
- `deploy.sh` - Main deployment script
- `rollback.sh` - Rollback to previous version
- `health-check.sh` - Post-deployment health checks

### Database (`database/`)
Database management scripts:
- `backup.sh` - Database backup script
- `restore.sh` - Database restore script
- `migrate.sh` - Run database migrations
- `seed.sh` - Seed database with initial data
- `reset.sh` - Reset database (caution: development only)

### Utilities (`utilities/`)
General utility scripts:
- `clean.sh` - Clean temporary files and caches
- `setup-dev.sh` - Set up development environment
- `generate-docs.sh` - Generate documentation
- `run-tests.sh` - Run test suites with specific configurations

## Usage

All scripts should be run from the project root directory:

```bash
# Make scripts executable
chmod +x scripts/**/*.sh

# Run a script
./scripts/database/backup.sh
```

## Best Practices

1. Make scripts idempotent where possible
2. Add proper error handling and logging
3. Document required environment variables
4. Test scripts in non-production environments first
5. Use meaningful exit codes
