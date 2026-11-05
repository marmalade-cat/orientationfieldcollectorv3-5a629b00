OrientationFieldCollectorV3

Tiny browser prototype to load per-module pose/orientation time-series (CSV or JSON), normalize timestamps, convert simple Euler or quaternion formats to a canonical CSV, and preview a lightweight WebGL orientation trace. No dependencies; open index.html in a browser.

Usage:
- Click "Load Sample" to try example data.
- Or paste JSON/CSV into the input area and click "Parse".
- Choose time column name and orientation format (euler or quat).
- Click "Export CSV" to download the normalized CSV.

Notes:
- This is a prototype for quick verification, not a high-precision production converter.
- Assumes right-handed coordinates; angles in degrees for Euler input.

Sample sources and inspiration: project goal supplied with this task.