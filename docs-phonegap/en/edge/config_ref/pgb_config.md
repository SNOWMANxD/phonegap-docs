---
license: Licensed to the Apache Software Foundation (ASF) under one
         or more contributor license agreements.  See the NOTICE file
         distributed with this work for additional information
         regarding copyright ownership.  The ASF licenses this file
         to you under the Apache License, Version 2.0 (the
         "License"); you may not use this file except in compliance
         with the License.  You may obtain a copy of the License at

           http://www.apache.org/licenses/LICENSE-2.0

         Unless required by applicable law or agreed to in writing,
         software distributed under the License is distributed on an
         "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
         KIND, either express or implied.  See the License for the
         specific language governing permissions and limitations
         under the License.
---

# PhoneGap Build Configuration

This section details configuration options available when using
PhoneGap Build to compile an application, or when using the _remote_
CLI option described in The Command-line Interface.  For overall
configuration options, see The config.xml File.  For information on
how to configure an app's graphics, see Icons and Splash Screens.

## Setting the PhoneGap Version

PhoneGap Build allows you to control which version of PhoneGap to use
when compiling a project remotely. Set the `phonegap-version`
preference to any of the following values: __2.0.0__, __2.1.0__,
__2.2.0__, __2.3.0__, __2.5.0__, __2.7.0__, or the default __2.9.0__:

        <preference name="phonegap-version" value="2.9.0" />

All PhoneGap versions prior to __2.0.0__ are deprecated. Specifying an
unsupported version number prevents the project from building.
