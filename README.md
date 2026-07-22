# PostgreSQL Tools Service

The PostgreSQL Tools Service (pgtoolsservice, or PGTS) is an application that provides core functionality for various PostgreSQL Server tools.
* Connection management
* Language Service support using VS Code protocol
* Query execution and resultset management
* Model Context Protocol (MCP) server

## PostgreSQL MCP server

[`@microsoft/postgres-mcp`](postgres-mcp/README.md) provides PostgreSQL tools and
connection utilities for MCP-compatible AI assistants.

## Telemetry

This project collects telemetry data through the related PostgreSQL for VS Code
extenension, which is used to help understand how to improve the product. For
example, this usage data helps to debug issues, such as slow start-up times, and
to prioritize new features. You can disable telemetry as described in the VS
Code [disable telemetry reporting] documentation.

The PostgreSQL MCP server also collects usage telemetry. Disable it with
`run --no-telemetry`.

Please see [PRIVACY](PRIVACY) for more information about data collection and use.

## Security reporting

Please see [SECURITY.md](SECURITY.md) for information on how to report security vulnerabilities.

## Code of Conduct

Please see [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) for information on our code of conduct.

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## License

The [MIT License](LICENSE) applies to both the pgsql-tools artifacts and the
PostgreSQL MCP server.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft
trademarks or logos is subject to and must follow
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.

[disable telemetry reporting]: https://code.visualstudio.com/docs/getstarted/telemetry#_disable-telemetry-reporting
