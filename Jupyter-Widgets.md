Jupyter Widgets is a system for providing interactive JavaScript controls for objects in a Jupyter kernel.

Here are some helpful resources about Jupyter widgets and where they are supported. These unofficial lists are maintained by the community at large in hopes they will be helpful. Listing here does not imply endorsement by Project Jupyter. These lists are certainly not comprehensive. Feel free to edit this page to include or update relevant information.

## Custom Jupyter Widgets

In addition to the projects below, you may also find custom Jupyter Widgets in the [jupyter-widgets GitHub topic](https://github.com/topics/jupyter-widgets).

| Name | Language | Description |
|------|-------------|-----|
| [ipywidgets](https://github.com/jupyter-widgets/ipywidgets/) | Python | Form controls (sliders, checkboxes, text inputs, date/color pickers) and containers (tabs, horizontal/vertical boxes, grid layout) |
| [ipyleaflet](https://github.com/jupyter-widgets/ipyleaflet) | Python | Geographic maps using leaflet |
| [pythreejs](https://github.com/jupyter-widgets/pythreejs) | Python | 3D library using three.js |
| [ipyflex](https://github.com/trungleduc/ipyflex)| Python | WYSIWYG layout editor for Jupyter Widgets |
| [bqplot](https://github.com/bqplot/bqplot) | Python | Python plotting library using d3js |
| [ipytree](https://github.com/QuantStack/ipytree) | Python | A Tree Widget using jsTree |
| [ipycanvas](https://github.com/martinRenou/ipycanvas) | Python | A Canvas Widget |
| [ipywebrtc](https://github.com/maartenbreddels/ipywebrtc) | Python | WebRTC in Jupyter |
| [ipyvolume](https://github.com/widgetti/ipyvolume) | Python | 3D plotting in Jupyter |
| [ipygany](https://github.com/QuantStack/ipygany) | Python | Scientific Visualization in Jupyter |
| [ipydatagrid](https://github.com/bloomberg/ipydatagrid) | Python | Fast Datagrid widget in Jupyter |
| [ipympl](https://github.com/matplotlib/ipympl) | Python | The Maptlotlib interactive backend |
| [xwidgets](https://github.com/jupyter-xeus/xwidgets) | C++ | The C++ counterpart for ipywidgets |
| [xcanvas](https://github.com/martinRenou/xcanvas) | C++ | A Canvas Widget |

## Frontends that support Jupyter widgets

| Name      |  Package to install | Core widget support    | Custom widget support | Examples | Notes |
|-----------|---------------------|------------------------|-----------------------|-------------------|-------|
| [JupyterLab](https://jupyterlab.readthedocs.io)| `jupyterlab-widgets` (ipywidgets installs this automatically) |  ✅  |  ✅  |
| [Jupyter Notebook](https://jupyter-notebook.readthedocs.io)| `widgetsnbextension` (ipywidgets installs this automatically) | ✅ | ✅ |


## Kernels that support Jupyter Widgets

| Name      | Language |  Package to install | Core widget support    | Custom widget support | Examples | Notes |
|-----------|----------|---------------------|------------------------|-----------------------|-------------------|-------|
| IPython/ipykernel | Python | `ipywidgets` |  ✅  |  ✅  |
| [xeus-python](https://github.com/jupyter-xeus/xeus-python) | Python | `ipywidgets` |  ✅  |  ✅  |
| [xeus-cling](https://github.com/jupyter-xeus/xeus-cling) | C++ |`xwidgets` |  ✅  |  ✅  |



