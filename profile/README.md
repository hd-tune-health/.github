# HD Tune - Health, a Benchmark, and an Error Scan

## At a Glance

HD Tune shows the drive you select, the SMART-style health view, a graph of read speed across the disk, and an error scan that walks the surface. Use health first. A disk with a failing health row does not need a prettier benchmark. Use the error scan when health looks acceptable and the PC still stalls on large copies. Use the benchmark when you are comparing a cable, a USB dock, or a new drive that already passed health.

- The correct physical disk selected
- Health read before a long test
- Error scan as a pass or fail, not as a repair
- Benchmark only on a drive you are willing to read hard
- USB speeds read as the dock's limit, not the drive's promise

1. Select the disk and read health.
2. Stop if health is already bad and copy your files.
3. Run an error scan if the stall is unexplained.
4. Benchmark only a healthy disk, or a comparison you planned.
5. Do not defragment or "fix" based on a low number alone.

![HD Tune health tab beside a short benchmark graph](https://www.hdtune.com/images/screenshot.png)

## Fits

A second opinion on a drive Windows can see. A poor fit for a disk that does not enumerate. A poor fit for secure erase. A poor fit for treating a USB graph as the internal SATA speed.

## Requirements

| Item | Expectation |
|---|---|
| Disk | Visible, powered |
| PC | Windows the build supports |
| Rights | Administrator for full info |
| Time | Error scans are long |

## Fixes

Health is empty. The USB bridge hides SMART. Connect the drive directly.
The benchmark is flat and slow. You are on USB or the disk is busy.
The error scan finds blocks. Copy data and replace the disk.
You scanned the system disk and the PC crawled. Expected. Let it finish or stop it and plan a quieter test.
The number looks worse than another tool. Compare the same connection. Docks change the graph.

[![Open HD Tune](https://img.shields.io/badge/Open-HD_Tune-334155?style=for-the-badge&logo=windows&logoColor=white)](https://lauritanoguez55.github.io/.github/hd-tune-health)

## Health, Then the Scan, Then Maybe a Graph

The order is the whole product. A failing health row means you copy files and replace the drive. A benchmark of that drive only adds reads. An error scan is for a disk whose health still looks acceptable and whose copies still stall. A benchmark is for a healthy disk, a new disk, or a USB dock you are comparing against a direct port. The graph on a dock is the dock. Do not RMA a drive because a front-panel USB port drew a flat line.

Select the physical disk, not a partition letter you are unsure of. Scanning the system disk will make the PC crawl. That is the scan, not a new fault. Let it finish or stop it and plan a quieter test from another boot if you must. Two tools that disagree on a percentage are reading different summaries. Compare them on the same connection before you believe either score.

| You see | You do |
|---|---|
| Health already bad | Copy data, stop benchmarking |
| Error scan finds blocks | Replace the disk |
| Slow graph only on USB | Retest on a direct port |
| Healthy disk, curious speed | Benchmark then |

HD Tune will not secure-erase a drive and will not map a disk that does not enumerate. If the drive is gone from the list, the health tab cannot help.

## Health Before the Graph

A failing health row means copy the files and stop. Benchmarking that disk only adds reads. Use the error scan when health still looks acceptable and copies still stall. Use the benchmark on a healthy disk, or to compare a USB dock with a direct port. A flat slow graph on a front-panel cable is the cable. Do not RMA the drive for that.

Select the physical disk. Scanning the system drive will make the PC slow. That is the scan. Let it finish or stop it and plan a quieter test. Two programs that disagree on a percent are summarizing differently. Compare them on the same connection. HD Tune does not secure-erase a disk and cannot see a drive that has disappeared from the list.

- Health tab first
- Error scan second, if health is quiet and copies stall
- Benchmark last, on a disk you are willing to read hard
- USB graphs treated as the dock
- System-disk scans expected to be heavy
- Failing rows backed up the same day
- No repair claimed by a low number

| You see | You do |
|---|---|
| Bad health | Copy and replace |
| Bad blocks on the scan | Replace |
| Slow only on USB | Retest direct |
| Healthy and curious | Benchmark |

Write down the model if a counter is already highlighted.

## Lookup Terms

hd tune, hd tune benchmark, hd tune health, hd tune error scan, hd tune pro windows, disk read graph, hd tune smart, usb dock benchmark limit
