# Copyright (C) 2007-2009 LuaDist.
# Created by Peter Kapec
# Redistribution and use of this file is allowed according to the terms of the MIT license.
# For details see the COPYRIGHT file distributed with LuaDist.
# Please note that the package source code is licensed under its own license.

PROJECT(luajson NONE)
CMAKE_MINIMUM_REQUIRED(VERSION 2.6)
INCLUDE(dist.cmake)

# Install all files and documentation
INSTALL (DIRECTORY lua/ DESTINATION ${INSTALL_LMOD})
INSTALL (FILES LICENSE README DESTINATION ${INSTALL_DATA})
INSTALL (DIRECTORY docs/ DESTINATION ${INSTALL_DOC})
INSTALL (DIRECTORY util/ DESTINATION ${INSTALL_FOO})
