# Google Street View for ArcGIS Pro

A lightweight ArcGIS Pro add-in that opens Google Street View from a clicked map location.

## Features

- Adds a `Google Street View` tab in ArcGIS Pro
- Adds an `Open Street View` map tool
- Click a location on the map to open Google Street View in your default browser
- Keeps the workflow simple and fast for map review

## Tested Environment

- ArcGIS Pro 3.x
- Windows
- Browser-based Google Street View launch

## Installation

### Option 1: Use the release package
1. Download `GoogleStreetView-PublicRelease.zip`
2. Extract the zip
3. Run `Install-GoogleStreetViewAddin.ps1`
4. Restart ArcGIS Pro if it is open

### Option 2: Manual install
1. Download `GoogleStreetView.esriAddinX`
2. Copy it to:

```text
%USERPROFILE%\Documents\ArcGIS\AddIns\ArcGISPro
```

3. Start or restart ArcGIS Pro

## Usage

1. Open ArcGIS Pro
2. Activate a map view
3. Go to the `Google Street View` tab
4. Click `Open Street View`
5. Click a location on the map
6. Google Street View opens in your default browser

## Notes

- Street View availability depends on Google coverage
- This add-in opens Google Street View in the browser
- It does not embed Google imagery inside ArcGIS Pro
- Use of Google Street View is subject to Google's terms and licensing

## Source

Main project files include:
- `Config.daml`
- `Module1.cs`
- `Buttons/OpenStreetViewTool.cs`

## Credits

James Bush

## License

MIT
