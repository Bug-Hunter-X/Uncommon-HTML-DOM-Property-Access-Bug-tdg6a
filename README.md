# Uncommon HTML Bug: Silent DOM Property Access

This repository demonstrates a subtle HTML bug related to accessing non-existent properties of DOM elements.  The code doesn't throw an immediate error, making it difficult to detect.  The bug is described in detail in `bug.html`, with a solution provided in `solution.html`.

The problem lies in the way that JavaScript interacts with the DOM, and how browsers handle attempts to access properties that don't exist on objects. Although it might seem harmless at first, this can lead to unexpected behavior or difficult-to-track errors later in the application.  The solution demonstrates a more robust approach that checks for the existence of properties before attempting access.

This bug serves as a good reminder to always perform appropriate error handling and input validation when working with the DOM and JavaScript in general.