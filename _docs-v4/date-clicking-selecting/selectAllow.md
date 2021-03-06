---
title: selectAllow
---

Exact programmatic control over where the user can select.

<div class='spec' markdown='1'>
function(selectInfo)
</div>

This callback will be called for every new potential selection as the user is dragging.

The callback function will receive information about where the user is attempting to select (`selectInfo`) and must return either `true` or `false`.

The `selectInfo` object will have the following properties:

- `start` (a [Date](date-object))
- `end` exclusive end date/time (a [Date](date-object))
- `resourceId` if you are using a [Resource View](scheduler)
