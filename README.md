# DDTank Calculator

> A modern, single-file calculator for DDTank players. Perfect your shot with the Full Angle technique.

DDTank Calculator is a lightweight web tool that helps you calculate the exact angle and force needed to hit your target in DDTank. It uses the classic **Full Angle** technique, one of the most accurate aiming methods in the game.

## Features

- Calculate the ideal angle based on distance and wind
- Support for wind direction (against or in favor)
- Real-time results with a clean, modern interface
- Themed with DDTank's colorful, playful visual identity
- Internationalization (i18n) support for English and Brazilian Portuguese
- Responsive design for mobile and desktop
- Zero dependencies. Single HTML file.
- No backend, no data collection, no tracking

## How It Works

The calculator uses the **Full Angle** formula:

```
Angle = 90 - Distance ± (Wind × 2)
```

- **Wind in favor (→):** Add to the angle (`+ Wind × 2`)
- **Wind against (←):** Subtract from the angle (`- Wind × 2`)
- **Force:** Always **95** (standard for Full Angle)

### Example

If the distance is 10 and the wind is 1.5 against you:

```
Angle = 90 - 10 - (1.5 × 2) = 77°
Force = 95
```

## Internationalization (i18n)

DDTank Calculator supports two languages:

- **English (en)**
- **Brazilian Portuguese (pt-BR)**

The language is automatically detected from the browser settings, and users can manually switch between languages using the toggle in the top-right corner. All UI text, labels, placeholders, and notes are translated.

## Getting Started

No installation required. Just open the HTML file in any modern browser.

```bash
git clone https://github.com/your-username/ddtank-calculator.git
cd ddtank-calculator
open index.html
```

Or simply download the `index.html` file and open it locally.

## Tech Stack

- HTML5
- CSS3 (custom properties, gradients, responsive design)
- Vanilla JavaScript (no frameworks, no libraries)
- Google Fonts (Fredoka + JetBrains Mono)

## Use Cases

- DDTank players who want to improve their accuracy
- Beginners learning the Full Angle technique
- Anyone who wants a quick, private aiming calculator without ads or tracking

## Limitations

- The formula is a simplified estimation based on the classic Full Angle technique. Actual results may vary depending on the weapon, terrain, and in-game physics.
- Wind values above 5.0 may produce less accurate results.
- Not affiliated with or endorsed by the original DDTank developers.

## Contributing

Contributions are welcome. Feel free to open an issue or submit a pull request.

1. Fork the repository
2. Create a branch: `git checkout -b feat/my-feature`
3. Commit your changes: `git commit -m "feat: my feature"`
4. Push: `git push origin feat/my-feature`
5. Open a Pull Request

## License

MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

Created by [Anderson Marlon (Yagasaki)](https://yagasaki.vercel.app)  
Feel free to reach out for feedback, suggestions, or collaboration.
