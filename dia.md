# dia.md · QUEAST Struktur

┌──────────────┐
│   SYS.js     │
└──────┬───────┘
       │
┌──────┴───────┐
│   core.js     │
└──────┬───────┘
       │
┌───────────────┼────────────────┐
│               │                │
│ axiom.js      │ axiom.map.js   │
│               │                │
└───────────────┴────────────────┘

      Kinder / Rooms
┌──────────────┬───────────────┬───────────────┐
│ HOLO.room.js │ NC.room.js     │ RESPO.room.js │
│ HOLO.engine  │ atom.js        │ beam.js       │
└──────────────┴───────────────┴───────────────┘

          Enkel
┌──────────────┬───────────────┬──────────────┐
│ rawator.js   │ rawator-life  │ rawator-81    │
│ geo.json     │ id.json       │ sli.ready     │
└──────────────┴───────────────┴──────────────┘

        Ahnen (HDF-ROM)
d.hdf.rom  e.hdf.rom  i.hdf.rom  
n.hdf.rom  o.hdf.rom  r.hdf.rom  
s.hdf.rom  u.hdf.rom  w.hdf.rom

        Gene (RAW)
d.raw  sli.ready  use.json  user.json

┌──────────────┐
│ index.html   │
└──────────────┘
