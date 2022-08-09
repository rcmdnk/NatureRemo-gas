# NatureRemo-gas
Google Apps Script for Nature Remo API

## Installation

* Make new [Google Spreadsheet](https://sheet.new).
* Open script editor: Tools->Script editor.
* Make new script files, and copy all gs files in this repository.
* Make another script file, named `secret` with contents:

        var ACCESS_TOKEN = '<YOUR_ACCESS_TOKEN>;

* You can generate new ACCESS_TOKEN for NatureRemo API at [NatureRemo's Access Tokens](https://home.nature.global/home) page.

## Configuration

### Appliances

In function
`appliances` in [NatureRemo.gs](https://github.com/rcmdnk/NatureRemo-gas/blob/main/NatureRemo.gs),
the script tries to find nicknames of an air conditioner and a light.

Their nicknames are defined in
[params.gss](https://github.com/rcmdnk/NatureRemo-gas/blob/main/params.gs).
as `エアコン` or `照明` for an air conditioner or light, respectively.

You may have difference nicknames for these appliances
then change these names.

In addition, your appliances may have difference parameters for each.
Please fix variables and column names in `appliances` function if necessary.



