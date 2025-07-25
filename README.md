# AW-Zombies-AutoTimers
A multi-functional LiveSplit script for Call of Duty: Advanced Warfare Zombies. 

# [Download v1.1](https://github.com/oJumpy/AW-Zombies-AutoTimers/releases/download/v1.1/AW.v1.1.asl)

## Setup
1. Download Livesplit [Site](https://livesplit.org/downloads/) or [Direct Link](https://github.com/LiveSplit/LiveSplit/releases/download/1.8.33/LiveSplit_1.8.33.zip)
1. Right Click LiveSplit → Edit Layout → `+` button → Control → Scriptable Auto Splitter → Browse to `AW.v1.1.asl` and select it.
1. If you want splits, refer to [Setting up Splits](#setting-up-splits) at this point.
1. Right Click LiveSplit → Compare Against → Select `Game Time`, Look down to where it says: *Best Segments*, *Average Segments*...
1. If you are using S1X Client. Make sure that you have the .exe named to just `s1x` in order to make the timer work!

## Setting up Splits
- Download [Blank Splits to 255](https://github.com/oJumpy/IW7-Zombies-AutoTimers/releases/download/v1/Blank.to.255.lss).
- Right Click LiveSplit → `Open Splits` → `From File...` → Browse to the splits file and select it.

## AutoSplitter Recommendations
- [My Layout](https://github.com/oJumpy/IW7-Zombies-AutoTimers/releases/download/v1/recommended_layout.lsl)

![image](https://github.com/user-attachments/assets/bc4814cd-a41c-4bf2-96f1-f2672858ae19)

## Custom Layouts
If you are going to make your own layout, make sure your LiveSplit is comparing against `Game Time` for everything. This includes `Subsplits`, `Splits`, `Timer`, `Detailed Timer`, etc.

For `Timing Method`, I recommend using `Current Timing Method`.

## Coming Soon
- Trap timers
- Error Trackers

## Unexpected behaviour
> [!WARNING]
> ### Reset Timer behaviour
> The reset timer may initially display an abnormally high value, in the 1000+ hours, at the start of a game. This issue resolves itself over time, and the timer will display correctly the longer you remain in a session. This is still being looked into.

## Known Issues
> [!CAUTION]
> These are some known issues with the timer, and will be fixed in the future.
> ### Saving layouts
> If you save your layout, with some settings enable you will encounter unexpected behavior. Example:
> - Duplicates Reset options and or other settings if enabled.
> - Timer size will get smaller
> ### Solution
> Save your layout only when you first loaded the script or click on `Reset to default` in the bottom right in `Scriptable Auto Splitter`, then save.
> I recommend to never save your layout whenever you enable additional settings.


