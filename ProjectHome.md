**Process Stalking** is a term coined by **Pedram Amini** to describe the combined process of run-time profiling, state mapping and tracing. Consisting of a series of tools and scripts the goal of a successful stalk is to provide the reverse engineer with an intuitive visual interface to filtered, meaningful, run-time block-level trace data.

The Process Stalker suite is broken into three main components; an **IDA Pro plug-in**, a stand alone tracing tool and a series of Python scripts for instrumenting intermediary and GML graph files. The generated GML graph definitions were designed for usage with a freely available interactive graph visualization tool.

Data instrumentation is accomplished through a series of Python utilities built on top of a fully documented custom API. Binaries, source code and in-depth documentation are available in the bundled archive. An indepth article was written and released on OpenRCE.org detailing step by step usage of Process Stalker, the article is a good starting point for understanding the basics behind the tool set:

> https://www.openrce.org/articles/full_view/12

A detailed software / usage manual and Python library reference is also available online at:

> http://pedram.redhive.com/process_stalking_manual/

> http://pedram.redhive.com/process_stalking_manual/ps_api_docs/

The original version by Pedram Amini can be downloaded from OpenRCE:

> http://www.openrce.org/downloads/details/171

This branch fixes compatibility issues with IDA Pro 5.x.