# md-website-cv

My template for rendering resumes/cv's with `pandoc` from `markdown`.

## Usage

### Dependencies

You will need the following for the `makefile` to run:

| OS | Package(s) |
| -- | -- |
| Arch Linux | `sudo pacman -S make pandoc && <aur-helper> -S wkhtmltopdf-static` |
| Debian | `sudo apt install make pandoc wkhtmltopdf -y` |
| Fedora | `sudo dnf install make pandoc wkhtmltopdf -y` |
| macOS | `brew install make pandoc && brew install --cask wkhtmltopdf` |
| Windows | <ol><li>`winget install -e --id ezwinports.make`</li><li>`winget install -e --id JohnMacFarlane.Pandoc`</li><li>`winget install -e --id wkhtmltopdf.wkhtmltox`</li></ol> |

### Running

Make your edits to `resume.md` with your favorite text editor, then run the makefile.

```bash
make
```

If you want only the `html` or the `pdf`, then run either

```bash
make html
```
or 
```bash
make pdf
```
respectively.

