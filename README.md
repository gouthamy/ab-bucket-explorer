# A/B Experiment Bucketing Visualizer

A modern, interactive tool to visualize how users are bucketed into A/B experiment variants using deterministic hashing.  
Great for demoing, debugging, or teaching A/B test bucketing logic!

## Features

- Enter any User ID and Experiment Name to see their assigned bucket (A, B, or Control)
- Animated hash calculation and assignment
- Visual bucket bar with color-coded segments
- Assignment history with advanced table view
- Fully client-side, no dependencies

## Usage

1. Clone or download this repository.
2. Open `index.html` in your browser.
3. Enter a User ID and Experiment Name, then click **Simulate** to see the result.

## Demo



## How It Works

- Uses a simple deterministic hash function to assign users to buckets.
- Buckets:  
  - **A:** 0–33%  
  - **B:** 33–66%  
  - **Control:** 66–100%

## Customization

- You can adjust bucket ranges, colors, or hashing logic by editing `index.html`.

## License

MIT

---

**Created by [Goutham Yenuganti]**
