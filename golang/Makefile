
BINARY_NAME=golang_example
OUTPUT_DIR=output

all: clean build

clean:
	@echo "Cleaning up..."
	@rm -rf $(OUTPUT_DIR)

build:
	@mkdir -p $(OUTPUT_DIR)
	@echo "Building the Go application..."
	go build -o $(OUTPUT_DIR)/$(BINARY_NAME) .

run: all
	@echo "Running the application..."
	@$(OUTPUT_DIR)/$(BINARY_NAME)