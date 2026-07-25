# QECC Gate Inspector

A lightweight gate-sequence viewer for quantum error correction circuits.

Inspired by [Crumble](https://algassert.com/crumble), but stripped down for speed — Crumble becomes sluggish on large circuits, and often all you need is to step through the gate sequence itself. This tool drops the heavy parts (Pauli marks, quantum circuit timeline rendering) to keep navigation fast even at scale.

## Keyboard Shortcuts

| Key | Action |
|---|---|
| `E` | Next tick |
| `Q` | Previous tick |
| `Space` + `E` | Next tick with a gate (skip empty ticks) |
| `Space` + `Q` | Previous tick with a gate (skip empty ticks) |
| `→` | Next tick containing a measurement |
| `←` | Previous tick containing a measurement |

## Snapshots

