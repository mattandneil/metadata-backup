# Metadata Backup - Ant Script

This macro will backup all metadata from an organization.

- Includes stubs for global components in managed packages
- Bulk retrieves when more than 10000 components
- Supports org sizes exceeding 50MB

Usage: _(paste the macrodef XML into your build file)_

```
<target name="backup">
    <backup
        username="${sf.username}"
        password="${sf.password}"
        serverurl="${sf.serverurl}"
    />
</target>
```