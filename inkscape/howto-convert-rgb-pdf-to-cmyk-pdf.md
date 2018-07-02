# Howto Convert RGB-pdf To CMYK-pdf

**Inkscape** needs a plugin to export to pdf in CMYK. However, it may be easier to use a terminal and **ghostscript**:

    gs -dSAFER -dBATCH \
        -dNOPAUSE -dNOCACHE -sDEVICE=pdfwrite \
        -sColorConversionStrategy=CMYK \
        -dProcessColorModel=/DeviceCMYK \
        -sOutputFile=cmyk-output.pdf \
        rgb-input.pdf
