<p align="center">
  <a href="https://github.com/swiftly-solution/vip_modules">
    <img src="https://cdn.swiftlycs2.net/swiftly-logo.png" alt="SwiftlyLogo" width="80" height="80">
  </a>

  <h3 align="center">[VIP] Custom FOV</h3>

  <p align="center">
    A module for <a href="https://github.com/swiftly-solution/vip-core">Swfitly VIP Core</a> that disables the flash effect for VIP Players (if they throwed it).
    <br/>
  </p>
</p>

---

### Dependencies 📃

- [Swiftly VIP Core Plugin](https://github.com/swiftly-solution/vip-core)

## Installation
1. Perform a drag-and-drop installation.
2. Add `fov` in the desired VIP Group in `addons/swiftly/configs/plugins/vips.json`.
### Example:
```json
	"groups": [
		{
			"id": "yourvip",
			"display_name": "VIP Group",
			"features": {
				"fov": 90.0, // (put , if you need to)
			}
		}
	],
```
3. Reload the configuration of the VIP by using `sw_adminvip`.

### Creating A Pull Request 😃

1. Fork the Project
2. Create your Feature Branch
3. Commit your Changes
4. Push to the Branch
5. Open a Pull Request

### Have ideas/Found bugs? 💡
Join [Swiftly Discord Server](https://swiftlycs2.net/discord) and send a message in the topic from `📕╎ plugins-sharing` named `[VIP] Modules`!


---