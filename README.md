This is an Angular web application that integrates with Google's Generative AI for building intelligent applications.

## Usage
First, add your AI Studio API key in the gemini.service file:
```typescript
this.genAI = new GoogleGenerativeAI('<paste API key here>');
```

Then start the development server:
```bash
ng serve
```

Your application will be running at `http://localhost:4200`


## Prerequisites
- Node.js (version 18.3 or higher)
- npm (comes with Node.js)
- Angular CLI
