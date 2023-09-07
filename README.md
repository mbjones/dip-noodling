# Distributed Info Package

A proposal for a data format.

## Layout of a package

```
package-1-example/
├── .dip
│   ├── objects
│   │   ├── 12
│   │   │   └── 3e
│   │   │       └── a45d21c9025a3d0f02de4088d4cb4e7eeb6246748edd883945b430b4a05d
│   │   ├── 7a
│   │   │   └── 1c
│   │   │       └── 82e3a1414dd90304cff20098bd0cc94a2134f77ae703b75c1020d4f49ed4
│   │   ├── 8b
│   │   │   └── 1d
│   │   │       └── d9de5a651508fed4c36dfb38fba591217c6fb177de0ec6f622ceb13f855c
│   │   ├── b2
│   │   │   └── b5
│   │   │       └── c5e08b48339246cd935a1a810c3030518a369c170d8693e59d5a5b58feab
│   │   └── fb
│   │       └── 4b
│   │           └── 3be4ad5fbba57436cc5327391df21802cfc8c14d1db1ab22fb32010189b2
│   ├── refs
│   │   └── tags
│   │       ├── 9f9853b3f13444197bd1c8eedb085b4c030a02ed28b5f61f3a6a1ba27bd1ae73
│   │       ├── acbbb742c7524cecdec7557d60e4a19af062346309ce5731c88485c7daf48982
│   │       ├── e05184c1f58012abeecc03933a7cc6b1e9f87b0d23de1f96993b154064ad8dca
│   │       ├── e579a69e6ffb88004b2f1bb290313704e76c156c8cf5f24ec870dd89472eca34
│   │       └── fbeae7c18667b6987518f3ae61ed8b19038e5961e8e7368597428eff76e4842a
│   └── sysmeta
│       ├── 9f9853b3f13444197bd1c8eedb085b4c030a02ed28b5f61f3a6a1ba27bd1ae73
│       ├── acbbb742c7524cecdec7557d60e4a19af062346309ce5731c88485c7daf48982
│       ├── e05184c1f58012abeecc03933a7cc6b1e9f87b0d23de1f96993b154064ad8dca
│       ├── e579a69e6ffb88004b2f1bb290313704e76c156c8cf5f24ec870dd89472eca34
│       └── fbeae7c18667b6987518f3ae61ed8b19038e5961e8e7368597428eff76e4842a
├── metadata
│   └── Greenhouse_gas_flux_measurements_at_the_zero.xml
├── plotobs.csv
└── raw
    ├── plot-orig.csv
    ├── site_data.csv
    └── survey_data.csv
```
