# Wombatsay
Print to stdout a picture of wombat with a phrase defined by either the program arguments or stdin

# Limitations

The speech bubble doesn't deal well with long strings tabs or newlines

# Usage

Print out fortune (with tabs replaced with spaces): 
    fortune | sed -e $'s/\t//g' | wombatsay
