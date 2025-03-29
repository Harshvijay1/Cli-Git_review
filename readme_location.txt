tests/README.md:TODO
src/utils/README.md:TODO
src/components/README.md:TODO
src/README.md:TODO
docs/specifications/README.md:TODO
docs/README.md:TODO
README.md:TODO

Single command to find all README.md file and output their paths to a file called readme_locations

grep -r --include "*.md" . > readme_location.txt
