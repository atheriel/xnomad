xnomad with bounded layouts
===========================

Note that this is a work in progress.

I don't really like the default look of [xnomad](https://github.com/fjolnir/xnomad)'s layouts, which take up the whole screen, so I've added a few new ones that add a bit of space around windows. The `border` width around the outside of all windows is configurable, as is the width of the `gutter` between them. See the `CustomLayouts.tq` file for the code in the layouts themselves.

Layouts
-------

An example of what I've christened the `StudioLayout`, to replace the default `MultiColLayout`:

![](http://i.imgur.com/MpqBYEOl.png)

As well as an example of a two-panel layout called, surprise, `PanelLayout`:

![](http://i.imgur.com/W7r1j27l.png)

There is also a replacement for the full-screen layout, `CenterStageLayout`:

![](http://i.imgur.com/H5jMs3ql.png)

about xnomad
------------

[xnomad](https://github.com/fjolnir/xnomad) is a tiling window manager for OS X written in [tranquil](https://github.com/fjolnir/tranquil).