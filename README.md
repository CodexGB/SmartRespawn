# SmartRespawn

SmartRespawn is a lightweight and permission-based plugin for Rust servers using uMod or Oxide. It allows configurable cooldowns for sleeping bags, beds, and beach towels, applying only to players who have a specific permission.

## Features

- Configure cooldowns for each deployable spawn item:
  - Sleeping bag
  - Bed
  - Beach towel
- Applies only to players with the `smartrespawn.use` permission
- Respects ownership of deployable spawn points
- Designed for PvE servers, donor perks, or quality of life improvements

## Configuration

The plugin generates the following configuration file at `oxide/config/SmartRespawn.json`:

```json
{
  "Cooldowns": {
    "bed_deployed": 1.0,
    "sleepingbag_leather_deployed": 1.0,
    "beachtowel_deployed": 1.0
  }
}
