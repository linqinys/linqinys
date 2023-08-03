### Hi there 👋

```

_removeMagnifyingGlass(evt) {
    
    const element = evt.detail.element;

    const magnifyCanvas = element.querySelector('.magnifyTool');
    if (magnifyCanvas) {
      console.warn('mouseUpCallback, ', evt.type)
    // Re-enable the mouse cursor
    setToolCursor(this.element, this.svgCursor);

    element.querySelector('.magnifyTool').style.display = 'none';
      this._removeZoomElement();
      
    }
    
  }


```
