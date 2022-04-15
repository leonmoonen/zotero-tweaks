
# the default location of Zotero is in the user's home directory but this can be configured
# see https://www.zotero.org/support/zotero_data
ZOTERO_LOCATION=~/Zotero

all:
	@echo "Running 'make install' will create a backup of the current Lookup Engine"
	@echo "configuration, and copy engines.json from this directory to the configured"
	@echo "location ($(ZOTERO_LOCATION)/locate/engines.json)."

install:
	mv $(ZOTERO_LOCATION)/locate/engines.json $(ZOTERO_LOCATION)/locate/engines.json-`date -u +%Y-%m-%dT%H:%M:%SZ`
	cp engines.json $(ZOTERO_LOCATION)/locate/engines.json
