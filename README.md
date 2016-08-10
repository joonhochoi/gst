# gst
based on ziutek's [Go bindings for GStreamer](https://github.com/ziutek/gst) and make some fixes

### Go bindings for GStreamer at a very early stage of maturity.

This package is based on [GLib bindings](https://github.com/lidouf/glib)<it's also based on ziutek's glib binding and make some fixes>. It
should be goinstalable. Try

    $ go get github.com/lidouf/gst

#### Documentation

See *examples* directory and http://gopkgdoc.appspot.com/pkg/github.com/ziutek/gst

To run examples use `go run` command:

	$ cd examples
	$ go run simple.go

To run live WebM example use `go run live_webm.go` and open
http://127.0.0.1:8080 with your browser. You probably need to wait a long time
for video because of small bitrate of this stream and big buffer in you browser.

### PROGRESS
#### GStreamer Core Library
    Gst                 11/12
    GstBin              6/21
    GstBus              16/24
    GstCaps             14/65
    GstClock            1/49
    GstElement          18/90
    GstElementFactory   7/19
    GstFormat           0/7
    GstInfo             0/86
    GstMessage          8/88
    GstObject           21/41
    GstPad              7/180
    GstPadTemplate      8/10
    GstPipeline         13/13
    GstQuery            3/96
    GstSegment          0/19
    GstStructure        3/69
    GstTagList          2/66
#### gst-plugins-base-libs
    GstDiscoverer       20/54
    GstVideoOverlay     1/7