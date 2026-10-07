# science.F

This repository is organized into a clear two-part structure:

- ScienceF: .NET 10 F# class library
- apps/frontend: React + Vite frontend site

## Structure

```text
science.F/
├── ScienceF/          # F# library
├── ScienceF.slnx      # .NET solution file
├── apps/
│   └── frontend/      # React frontend app
└── README.md
```

## Run the frontend

```bash
cd apps/frontend
npm install
npm run dev
```

## Build the .NET library

```bash
dotnet build ScienceF.slnx
```

## Build the frontend

```bash
cd apps/frontend
npm run build
```