All right and credit to Nipun Batra, https://nipunbatra.github.io/blog/2014/latexify.html

Installation:

    pip install git+git@github.com:kidmose/ppfl.git#egg=ppfl

Usage: 

    # import 
    from ppfl import latexify, format_axes
    # Setup (once. before plotting)
    latexify()
    # fix axes (every time, just before saving, after tight_layout)
    format_axes(ax) 
    # Alternatively `format_axes(plt.gca())` 
    # assuming `import matplotlib.pyplot as plt`



    
