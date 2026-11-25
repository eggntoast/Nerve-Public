# Help

## Before reporting a problem

Check that you installed the latest [Nerve Forever release](downloads.md). Nerve currently supports Warrior; the other classes are planned. The TBC version is no longer maintained.

For installation and previews, start with the [setup guide](getting-started.md).

## If Nerve will not open

A startup failure in **0.1.2** has been confirmed after the latest Forever update: the game no longer supplies the realm name that older profiles used. A correction is being tested. Keep your saved settings; deleting them will not fix this missing realm information.

Restart the game or use **/reload** with Nerve enabled. If it still will not open, report the first Nerve Lua error and your game version and build. If **About** is unavailable, include the version you installed from CurseForge instead. Keep your saved settings; you do not need to delete them to report the problem.

## If an overlay is missing

* Select the ability and check that **Enabled** is on.
* If you want overlays outside combat, turn off **Settings → Behavior → Only in combat**.
* Check the ability order and **Display options**. Another active ability may have priority.

Victory Rush stays hidden during its own cooldown, even when a fresh Victorious buff is present.

**/nerve diag** shows ability status and explains why the Victory Rush overlay is hidden. Include the relevant output when reporting a problem.

## Report a problem

[Open a bug report](https://github.com/eggntoast/Nerve-Public/issues/new/choose) and include:

* Your Nerve version and build from **About**.
* Your game client and game version.
* What you did, what happened and what you expected.
* Any Lua error. A screenshot can help with visual problems.

Hide personal information in screenshots. You don’t need to upload a full SavedVariables file to make a report.

## Suggestions

[Share an idea](https://github.com/eggntoast/Nerve-Public/issues/new/choose). Tell us what you’d like to do and how it would help while playing.

## Current limits

* Warrior is the only available class; the other classes are planned.
* Victory Rush is supported in WoW Forever. Its fade needs readable buff timing; when the game does not provide that timing, the overlay stays steady.
* The animated style previews are rendered outside WoW and haven’t been compared with the game yet. The settings screenshot comes from the older TBC version.

[Changelog](../CHANGELOG.md) · [Downloads](downloads.md) · [Back to Nerve](../README.md)
