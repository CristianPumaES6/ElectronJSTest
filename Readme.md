#ElectronJS

Note: If the main field is not present in package.json, Electron will attempt to load an index.js (as Node.js does).

Turning this Node application into an Electron application 
{
  "name": "your-app",
  "version": "0.1.0",
  "main": "main.js",
  "scripts": {
    "start": "electron ."
  }
}