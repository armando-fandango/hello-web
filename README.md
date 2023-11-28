# hello-web
Hello Web Sample Project - Empty - Pull requests welcome.

- Change the `.env` file to match your environment and then open in container inside vscode.
- Remove /data:/data in docker-compose.yml if you don't want have this volume to mount.

Based on:

- Alpine Linux v3.18
- node v21.2.0
- npm 10.2.3
- yarn 1.22.21
- pnpm 8.11.0

To create and develop the app:

```bash
pnpm create next-app hello-app --ts --tailwind --eslint --app --src-dir --import-alias "@/*" --use-pnpm
pnpm dev
```