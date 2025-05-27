# CSV to VCF Converter

This is a simple web app to convert CSV files into bulk `.vcf` (vCard) files.

## Features

- Supports bulk conversion
- No installation required
- Easy to use, clean UI
- Exported `.vcf` supports mobile importing

## CSV Format

Your CSV file must follow this structure:

First Name, Last Name, Phone Number

Ex: Donald,Trump,011234567

## Usage

1. Open `index.html` in any browser.
2. Click the upload button and select your CSV file.
3. Click **Convert**.
4. Download the generated `.vcf` file.

## Live Preview (Optional)

You can deploy this on GitHub Pages:

## License

This project is licensed under the [MIT License](LICENSE).
```bash
git branch -M main
git push origin main
git add LICENSE
git commit -m "Add MIT license"
git push
