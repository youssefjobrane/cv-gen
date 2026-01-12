# CV Generator

A simple, modern CV generator that creates professional resumes from JSON data. The project supports multiple languages and provides a clean, responsive design.

## Features

- Multi-language support (English and French)
- Responsive design that works on all devices
- Easy-to-edit JSON data files
- Clean, professional template
- Print-friendly layout

## Getting Started

### Prerequisites

- Python 3.x (for local development server)
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor for editing JSON files

### Local Development

To view and test your CV locally, you can use Python's built-in HTTP server:

1. Open a terminal or command prompt
2. Navigate to your project directory:
   ```bash
   cd path/to/your/cv-project
   ```
3. Start the local server on port 8000:
   ```
   python -m http.server 8000
   ```
4. Open your web browser and visit:
   ```
   http://localhost:8000/template.html
   ```

**Note:** If port 8000 is already in use, you can specify a different port (e.g., 8080):
```
python -m http.server 8080
```
Then access it at `http://localhost:8080`

## Updating Your CV

1. Edit the JSON files to update your information:
   - `cv-data-en.json` - English version
   - `cv-data-fr.json` - French version

2. The CV will automatically update when you refresh the browser

## Available Data Sections

- Personal information
- Professional summary
- Work experience
- Education
- Skills
- Languages
- Certifications
- Projects

## Customization

### Styling

You can customize the appearance by modifying the CSS in the `template.html` file. Look for the `<style>` tag to adjust colors, fonts, and layout.

### Adding New Languages

1. Create a new JSON file (e.g., `cv-data-es.json` for Spanish)
2. Follow the same structure as the existing JSON files
3. Add language switching functionality to the template if needed

## Printing

Use your browser's print function (Ctrl+P or Cmd+P) to save your CV as a PDF.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

