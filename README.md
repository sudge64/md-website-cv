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


## Notices

The file `style.css` is copyright Christophe-Marie Duquesne <chmd@chmd.fr> and licensed under CC BY-SA 3.0.

I have modified the colors and aspects of the spacing.

The original notice:

> Copyright 2013 Christophe-Marie Duquesne <chmd@chmd.fr>
>
> CSS for making a resume with pandoc. Inspired by moderncv.
>
> This CSS document is delivered to you under the CC BY-SA 3.0 License.
> https://creativecommons.org/licenses/by-sa/3.0/deed.en_US

