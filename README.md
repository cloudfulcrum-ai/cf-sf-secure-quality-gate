# Secure Quality Gate

**cf-sf-secure-quality-gate**

    Runs security and code quality checks before deployment.

* **Inputs**:
    * **source-directory**: Path to source files.

* **Outputs**:
    * **quality-report**: Path to the generated quality report.

Usage Example:

    - name: Run Security & Quality Checks
      uses: ghcr.io/itfulcrum/cf-sf-secure-quality-gate@latest
      with:
      source-directory: "./src"
## Installation & Usage

To use these GitHub Actions, ensure that your repository has:

* A .github/workflows/ directory for defining workflows.
* Necessary Salesforce authentication secrets configured in GitHub Actions.

## Contributing

Feel free to submit pull requests to improve existing actions or add new functionality.

## License

This project is licensed under the MIT License.