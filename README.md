# trunk-service - AWS CI Pipeline

CI/CD base generated for AWS CodeBuild/CodePipeline.

## Configuration

- **Language**: nodejs
- **Ambientes**: dev=, qa=, prod=
- **Rama inicial del repo**: main
- **AWS Region**: us-east-2
- **AWS Account**: 039438367923

## Included build steps
- {{ step }}
- {{ step }}
- {{ step }}
- {{ step }}
- {{ step }}
- {{ step }}
- {{ step }}

## Generated files

```
.
├── buildspec.yml
├── Dockerfile
├── catalog-info.yaml
└── openapi.yaml
```

## API (Backstage)

La pestaña **API** del catálogo usa `catalog-info.yaml` (`providesApis`) y
`openapi.yaml` (contrato OpenAPI de ejemplo: `/`, `/live`, `/ready`).
Actualiza `openapi.yaml` cuando agregues endpoints nuevos.

## Next steps

1. Push these files to your repository.
2. Create/Update AWS CodeBuild project and point to this `buildspec.yml`.
3. (Optional) Create AWS CodePipeline and connect your source + CodeBuild stage.
