# we don’t want to use relative paths, so we set these variables
PROJECT_DIR=/home/sandeep/Desktop/DEV/CPPU_TEST/spark/
SRC_DIR=$(PROJECT_DIR)/src
TEST_DIR=$(PROJECT_DIR)/t
# specify where the source code and includes are located
INCLUDE_DIRS=$(SRC_DIR)/code
SRC_DIRS=$(SRC_DIR)/code

# specify where the test code is located
TEST_SRC_DIRS = $(TEST_DIR)

# what to call the test binary
TEST_TARGET=example

# where the cpputest library is located
#CPPUTEST_HOME=/usr/local

# run MakefileWorker.mk with the variables defined here
include $(CPPUTEST_HOME)/build/MakefileWorker.mk
