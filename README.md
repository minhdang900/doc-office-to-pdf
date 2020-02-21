## Setup

`docker build -t xtopdf:latest .`
`docker run --rm --name si-xtopdf -v PATH_FOLDER:/tmp xtopdf libreoffice --headless --convert-to pdf /tmp/XSL_FILE --outdir /tmp/pdf`

## Reference [link](https://michalzalecki.com/converting-docx-to-pdf-using-python/)