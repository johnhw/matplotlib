Removals
--------
The following deprecated APIs have been removed:

Classes and methods
~~~~~~~~~~~~~~~~~~~
- ``backend_bases.RendererBase.strip_math()``
  (use ``cbook.strip_math()`` instead)

- ``backend_wx.debug_on_error()`` (no replacement)
- ``backend_wx.raise_msg_to_str()`` (no replacement)
- ``backend_wx.fake_stderr`` (no replacement)
- ``backend_wx.MenuButtonWx`` (no replacement)
- ``backend_wx.PrintoutWx`` (no replacement)
- ``_backend_tk.NavigationToolbar2Tk.set_active()`` (no replacement)

- ``backend_ps.PsBackendHelper.gs_exe`` property (no replacement)
- ``backend_ps.PsBackendHelper.gs_version`` property (no replacement)
- ``backend_ps.PsBackendHelper.supports_ps2write`` property (no replacement)
- ``backend_ps.RendererPS.afmfontd`` property (no replacement)
- ``backend_ps.GraphicsContextPS.shouldstroke`` property (no replacement)

- ``backend_gtk3.FileChooserDialog`` (no replacement)
- ``backend_gtk3.SaveFigureGTK3.get_filechooser()`` (no replacement)
- ``backend_gtk3.NavigationToolbar2GTK3.get_filechooser()`` (no replacement)

- ``backend_gtk3cairo.FigureManagerGTK3Cairo``
  (use ``backend_gtk3.FigureManagerGTK3`` instead)

- ``backend_pdf.RendererPdf.afm_font_cache`` property (no replacement)

- ``backend_pgf.LatexManagerFactory`` (no replacement)

- ``backend_qt5.NavigationToolbar2QT.buttons`` property (no replacement)
- ``backend_qt5.NavigationToolbar2QT.adj_window`` property (no replacement)

- ``matplotlib.checkdep_dvipng`` (no replacement)
- ``matplotlib.checkdep_ghostscript`` (no replacement)
- ``matplotlib.checkdep_pdftops`` (no replacement)
- ``matplotlib.checkdep_inkscape`` (no replacement)
- ``matplotlib.get_py2exe_datafiles`` (no replacement)
- ``matplotlib.tk_window_focus`` (use ``rcParams['tk.window_focus']`` instead)

- ``pyplot.plotfile()`` (Instead, load the data using
  `pandas.read_csv` or `numpy.loadtxt` or similar and use regular pyplot
  functions to plot the loaded data.)
- ``rcsetup.validate_qt4()`` (no replacement)
- ``rcsetup.validate_qt5()`` (no replacement)
- ``rcsetup.validate_verbose()`` (no replacement)
- ``rcsetup.ValidateInterval`` (no replacement)

- ``sphinxext.plot_directive.plot_directive()``
  (use the class ``PlotDirective`` instead)

- ``Artist.aname`` property (no replacement)
- ``Axis.iter_ticks`` (no replacement)

- ``image.BboxImage.interp_at_native`` property (no replacement)
- ``lines.Line2D.verticalOffset`` property (no replacement)
- ``bezier.find_r_to_boundary_of_closedpath()`` (no relacement)

- ``quiver.Quiver.color()`` (use ``Quiver.get_facecolor()`` instead)
- ``quiver.Quiver.keyvec`` property (no replacement)
- ``quiver.Quiver.keytext`` property (no replacement)

- ``colorbar.ColorbarBase.get_cmap`` (use ``ScalarMappable.get_cmap`` instead)
- ``colorbar.ColorbarBase.set_cmap`` (use ``ScalarMappable.set_cmap`` instead)
- ``colorbar.ColorbarBase.get_clim`` (use ``ScalarMappable.get_clim`` instead)
- ``colorbar.ColorbarBase.set_clim`` (use ``ScalarMappable.set_clim`` instead)
- ``colorbar.ColorbarBase.set_norm`` (use ``ScalarMappable.set_norm`` instead)
