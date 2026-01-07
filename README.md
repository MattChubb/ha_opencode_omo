# Home Assistant Add-on: HA OpenCode

[![GitHub Release][releases-shield]][releases]
[![License][license-shield]](LICENSE)
![Project Stage][project-stage-shield]
![Maintenance][maintenance-shield]

![Supports aarch64 Architecture][aarch64-shield]
![Supports amd64 Architecture][amd64-shield]

AI-powered coding agent for Home Assistant configuration.

## About

HA OpenCode brings the power of AI-assisted coding directly to your Home Assistant instance. Edit your configuration files using natural language, get intelligent YAML assistance, and leverage deep Home Assistant integration through MCP (Model Context Protocol).

### Key Features

- **AI-Powered Editing** - Use natural language to modify your Home Assistant configuration
- **Modern Web Terminal** - Beautiful terminal with 10 theme options, accessible from the HA sidebar
- **Provider Agnostic** - Works with Anthropic, OpenAI, Google, and 70+ other AI providers
- **MCP Integration** - 19 tools, 9 resources, and 6 guided prompts for deep HA integration
- **LSP Support** - Intelligent YAML editing with entity autocomplete, hover info, and diagnostics
- **Log Access** - View Home Assistant Core, Supervisor, and host logs directly
- **Ingress Support** - Secure access through Home Assistant authentication

[:books: Read the full add-on documentation][addon-doc-ha-opencode]

## Warning

This add-on has **read/write access** to your Home Assistant configuration directory. While the AI is instructed to ask for confirmation before making changes, please:

- Always back up your configuration before making significant changes
- Review changes suggested by the AI before accepting them
- Keep your configuration under version control (git) when possible

## Installation

1. Click the button below to add this repository to your Home Assistant instance:

   [![Add Repository][repo-btn]][repo-add]

   Or manually add the repository URL:
   ```
   https://github.com/magnusoverli/ha_opencode
   ```

2. Find **"HA OpenCode"** in the add-on store and click **Install**.

3. Start the add-on and click **Open Web UI** (or use the sidebar).

4. Run `opencode` and use `/connect` to configure your AI provider.

## Add-ons in this repository

### &#10003; [HA OpenCode][addon-ha-opencode]

![Latest Version][ha-opencode-version-shield]
![Supports aarch64][aarch64-shield]
![Supports amd64][amd64-shield]

AI coding agent for editing Home Assistant configuration with intelligent YAML assistance.

[:books: HA OpenCode documentation][addon-doc-ha-opencode]

## Support

Got questions or issues?

- [Open an issue on GitHub][issues]
- [OpenCode Documentation](https://opencode.ai/docs)
- [OpenCode Discord](https://opencode.ai/discord)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Authors & Contributors

- **Magnus Overli** - *Initial work* - [magnusoverli](https://github.com/magnusoverli)

See the [contributors](https://github.com/magnusoverli/ha_opencode/graphs/contributors) page for a full list of contributors.

## License

MIT License - see [LICENSE](LICENSE) for details.

[addon-ha-opencode]: ./ha_opencode
[addon-doc-ha-opencode]: ./ha_opencode/DOCS.md
[issues]: https://github.com/magnusoverli/ha_opencode/issues
[releases]: https://github.com/magnusoverli/ha_opencode/releases
[releases-shield]: https://img.shields.io/github/release/magnusoverli/ha_opencode.svg
[repo-add]: https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fmagnusoverli%2Fha_opencode
[repo-btn]: https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg

[license-shield]: https://img.shields.io/github/license/magnusoverli/ha_opencode.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2026.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-experimental-orange.svg
[ha-opencode-version-shield]: https://img.shields.io/badge/version-v1.0.9-blue.svg
[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
