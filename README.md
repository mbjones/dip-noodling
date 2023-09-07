# Distributed Info Package

A proposal for a data format.

## Layout of a package

```
package-1-example
├── .dip
│   ├── objects
│   │   ├── 12
│   │   │   └── 3e
│   │   │       └── a45d21c9025a3d0f02de4088d4cb4e7eeb6246748edd883945b430b4a05d
│   │   ├── 2b
│   │   │   └── 44
│   │   │       └── 7b5885f9b40c864ea49594a5b31fcb6e2a321c1732346e8296fe14a1dcdc
│   │   ├── 59
│   │   │   └── 9c
│   │   │       └── 521e652062bca90071b72ffc9780e97e3bcf3213630b390c0bb703594f60
│   │   ├── 71
│   │   │   └── 29
│   │   │       └── a7fac461d084afc4476e6b72156fef11b3784286cf698742fb3a6ba7e5f2
│   │   ├── 7a
│   │   │   └── 1c
│   │   │       └── 82e3a1414dd90304cff20098bd0cc94a2134f77ae703b75c1020d4f49ed4
│   │   ├── 7b
│   │   │   └── ec
│   │   │       └── d1b7e758b87c25dba4357b2bd298ba0e14dbe546ce88b108696fd93ba6c1
│   │   ├── 7d
│   │   │   └── d8
│   │   │       └── c63363ace47dc97a34eeef6042b6023a43adb8ee36e4305b3917d545648e
│   │   ├── 8b
│   │   │   └── 1d
│   │   │       └── d9de5a651508fed4c36dfb38fba591217c6fb177de0ec6f622ceb13f855c
│   │   ├── 96
│   │   │   └── 65
│   │   │       └── 15904c84bb95535c62b7865f4be638b0720f183c01ad0d2720c5f60ea2cc
│   │   ├── b2
│   │   │   └── b5
│   │   │       └── c5e08b48339246cd935a1a810c3030518a369c170d8693e59d5a5b58feab
│   │   ├── f6
│   │   │   ├── 0f
│   │   │   │   └── 3dbecc938b5fa329ef7eaf09c13612962ada8e864adcecc3e4b104f685d4
│   │   │   └── b5
│   │   │       └── c3fd3082a3c483a705c1ab7988fe690e47232063fc6a70e5cba0ab37968d
│   │   └── fb
│   │       └── 4b
│   │           └── 3be4ad5fbba57436cc5327391df21802cfc8c14d1db1ab22fb32010189b2
│   ├── refs
│   │   └── tags
│   │       ├── 65
│   │       │   └── 30
│   │       │       └── f774a5f130efbd0d0282736a21a9b92d19e48b9ca71782be30ad37c5e756
│   │       ├── 9c
│   │       │   └── 26
│   │       │       └── 4d5caeb5a7868caa70d9364514a9149aa3c764937a35378ea2906d81bf35
│   │       ├── 9f
│   │       │   └── 98
│   │       │       └── 53b3f13444197bd1c8eedb085b4c030a02ed28b5f61f3a6a1ba27bd1ae73
│   │       ├── ac
│   │       │   └── bb
│   │       │       └── b742c7524cecdec7557d60e4a19af062346309ce5731c88485c7daf48982
│   │       ├── e0
│   │       │   └── 51
│   │       │       └── 84c1f58012abeecc03933a7cc6b1e9f87b0d23de1f96993b154064ad8dca
│   │       ├── e5
│   │       │   └── 79
│   │       │       └── a69e6ffb88004b2f1bb290313704e76c156c8cf5f24ec870dd89472eca34
│   │       └── fb
│   │           └── ea
│   │               └── e7c18667b6987518f3ae61ed8b19038e5961e8e7368597428eff76e4842a
│   └── sysmeta
│       ├── 9c
│       │   └── 26
│       │       └── 4d5caeb5a7868caa70d9364514a9149aa3c764937a35378ea2906d81bf35
│       ├── 9f
│       │   └── 98
│       │       └── 53b3f13444197bd1c8eedb085b4c030a02ed28b5f61f3a6a1ba27bd1ae73
│       ├── ac
│       │   └── bb
│       │       └── b742c7524cecdec7557d60e4a19af062346309ce5731c88485c7daf48982
│       ├── e0
│       │   └── 51
│       │       └── 84c1f58012abeecc03933a7cc6b1e9f87b0d23de1f96993b154064ad8dca
│       ├── e5
│       │   └── 79
│       │       └── a69e6ffb88004b2f1bb290313704e76c156c8cf5f24ec870dd89472eca34
│       └── fb
│           └── ea
│               └── e7c18667b6987518f3ae61ed8b19038e5961e8e7368597428eff76e4842a
├── metadata
│   ├── Greenhouse_gas_flux_measurements_at_the_zero.xml
│   └── ore-resource-map.xml
├── plotobs.csv
└── raw
    ├── plot-orig.csv
    ├── site_data.csv
    └── survey_data.csv
```
