# bash-api-test
Simple bash script to test REST APIs with templates.

## Usage
```bash
./apitest <TEMPLATE_NAME>
```

## Templates
Templates are stored in the `api_templates` directory. Each template has the following structure:
```
METHOD=<METHOD>
URL=<URL>
HEADERS=""
```

## Example
```bash
./apitest default
``` 

