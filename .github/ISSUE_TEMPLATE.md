---
title: {{ env.VERSION }}
labels: release
---
# Author: 

{{ payload.sender.login }}


# Date: 

{{ date | date('D MMMM YYYY') }}


# Version: 

{{ env.VERSION }}


# Changelog: 

{{ env.CHANGELOG }}


# Checks

{{ env.CHECKS_LINK }}