#
# Copyright 2016 Jeff Bush
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
#

all:
	cd libc && make
	cd librender && make
	cd libos && make
	cd compiler-rt && make
	cd libconsole && make

clean:
	cd libc && make clean
	cd librender && make clean
	cd libos && make clean
	cd compiler-rt && make clean
	cd libconsole && make clean


