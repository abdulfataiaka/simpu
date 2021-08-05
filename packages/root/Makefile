.DEFAULT_GOAL := help

##----------------------------------------------------------------------------------------------------------------------
##@ Root Commands

help: ## List of all commands available
	@awk 'BEGIN {FS = ":.*##"; printf "\n"} /^[a-zA-Z0-9_-]+:.*?##/ { printf "  \033[36m%-15s\033[0m %s\n\n", $$1, $$2 } /^##@/ { printf "\033[1m%s\n\033[0m\n", substr($$0, 5) } ' $(MAKEFILE_LIST)
