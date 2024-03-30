# kuku
This is an app that training kuku.

# Development Info
* Docker: node:20-slim

## Run Environment
Run container.
```bash
docker compose up -d
```

Enter container shell
```bash
docker compose exec front bash
```

Run React app in container.
```
cd kuku
npm run dev
```

And access `http://localhost:13000/`.

## Setup Log
```bash
✔ What is your project named? … kuku
✔ Would you like to use TypeScript? … No / "Yes"
✔ Would you like to use ESLint? … No / "Yes"
✔ Would you like to use Tailwind CSS? … No / "Yes"
✔ Would you like to use `src/` directory? … No / "Yes"
✔ Would you like to use App Router? (recommended) … No / "Yes"
✔ Would you like to customize the default import alias (@/*)? … "No" / Yes
```
