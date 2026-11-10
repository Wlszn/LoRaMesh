# LoRaMesh — Off-grid messaging with LoRa and MeshCore

**Course:** Advanced Networks (420-521-VA), Vanier College — Fall 2026
**Instructor:** Tiago Bortoletto Vaz
**License:** MIT (see [LICENSE](LICENSE))

## Team
| Name | Student ID |
|---|---|
| Willkerdy Elveus | TODO |
| Mohamed Amine Hamidouch | TODO |
| Sean Lussier | TODO |

## Topic
LoRa and MeshCore

## What we are building
We are building a small LoRa mesh network of three devices running MeshCore firmware to show
that messages can be exchanged without Wi-Fi, cellular or Internet access. Two devices act as
companion nodes and one acts as a repeater that forwards messages when the two companions
cannot reach each other directly. We will measure how distance and obstacles affect signal
strength, compare MeshCore with Meshtastic and Reticulum/RNode, and estimate the solar panel
and battery a repeater would need to run through a Montreal winter.

## Live host
No server needed. The network runs entirely on the LoRa devices, off-grid.
Devices are flashed and configured from: TODO (exact laptop model)

## How to reproduce our setup
> Fill this in as you go. Only list steps that actually worked.

1. Hardware: TODO (exact board model × 3, antennas, USB cables, power)
2. Flash MeshCore: TODO (flasher used, firmware version, role per device)
3. Configure: TODO (region/frequency preset, node names, channel — no secrets here)
4. Connect a client: TODO (companion app and how it pairs)
5. Test: TODO (send a message between the companions, then through the repeater)

## Repository layout
| Path | Contents |
|---|---|
| `slides/` | Presentation (PDF) |
| `src/` | Code and scripts |
| `config/` | Configuration files, secrets removed |
| `docs/plan/` | Lab 7 proposal and Lab 9 design |
| `docs/report/` | Final report |
| `evidence/` | Screenshots, notes, command output |
