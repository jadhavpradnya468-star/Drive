

# Drive - File Upload/Download App

Simple Node.js + Express file upload and download application using EJS views.

## Install

Install dependencies:

```bash
npm install
```

## Run

Start the server (default port 3000):

```bash
node app.js
# or with an environment variable
PORT=4000 node app.js
```

Open http://localhost:3000 in your browser.

## Usage / Example

- The home page contains the upload form (views/*.ejs).
- API routes are under `/api/files` and user routes under `/api/users`.

Upload a file using the form on the site, or with `curl`:

```bash
curl -v -F "file=@/path/to/yourfile.jpg" http://localhost:3000/upload-file
```

Download a file directly (served from `/uploads`):

```bash
curl -O http://localhost:3000/uploads/yourfile.jpg
```

## Notes

- Views are in the `views/` directory.
- Uploaded files are stored in the `uploads/` directory and served statically.
- See `app.js` for server startup and route mounting.

If you want me to include a specific code snippet from one of the project files, tell me which file and I'll add it here.

