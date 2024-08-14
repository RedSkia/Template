## Project Structuring
- {SolutionName}/
	- {ProjectName}/
		- src/
			- {ComponentCategory}/
                - {ComponentName}
		- assets/
			- {AssetCategory}/
		- data/
			- {DataCategory}/
		- tests/
			- {ComponentCategory}/
				- {ComponentName}**.**{TestCase}
		- bin/
			- executables...
		- lib/
			- dependencies...
		- docs/
			- {DocumentCategory}.md
	- {Additions}/
		- {NameOfAdditional}

## Branch Strategy (Github flow)
| main | category/name |
| :-: | :-: |
| Houses the production-ready solution. Continuously integrated with the latest stable branches. | Categorises development work based on solution type. (e.g., feature/name, fix/login) Merges into the `main` branch upon PR approval. |

## Workflow Strategy (CDPRRD)
- **Create** a new branch derived from the `main` branch, using the specified **Branch Strategy**.
- **Develop** and commit necessary changes to the solution branch.
- **Pull Request** submission is permissible upon completion of the development cycle, provided the solution branch is stable for integration into the `main` branch.
- **Review** of the PR ensures adherence to best practices, and verifies the solution's suitability for integration into the `main` branch.
- **Deletion** of the development branch occurs upon successful PR approval, and merging into the `main` branch.