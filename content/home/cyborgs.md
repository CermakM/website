+++
# Showcase widget.
widget = "showcase"
active = true

# Title and subtitle
title = 'Cyborgs'
subtitle = "Our junior team members."

# Order that this section will appear in (if applicable).
weight = 5

# Tiles
# Add tiles by appending new `[[tile]]` specifications.
# :param identifier [optional]
# :param title
# :param text
# :param icon: icon from /images/illustrations/icons
# :param button: Tile.Button object

# Tile.Button
# :param modal: if specified, which modal to use [card, steps]
# :param link: (not applicable for modal buttons)
# :param data: data for the modal card, if not provided, identifier is used
# :param target: target for the modal card, if not provided, identifier is used

[[tile]]
  identifier = 'kebechet'
  modal = true
  title = "Kebechet"
  text = "This is some explanatory text that is on two rows"
  icon = 'plug-cloud.svg'
  [tile.button]
    marker = 'success'
    target = "kebechet-setup"
    text = "GET STARTED"
  [tile.label]
    target = 'kebechet-readme'
    text = "README"

[[tile]]
  identifier = 'sesheta'
  modal = true
  title = "Sesheta"
  text = "This is some explanatory text that is on two rows"
  icon = 'plug-cloud.svg'
  [tile.button]
    marker = 'success'
    text = "GET STARTED"
  [tile.label]
    target = 'sesheta-readme'
    text = "README"

[[tile]]
  identifier = 'appbot'
  title = "<app bot>"
  text = "This is some explanatory text that is on two rows"
  icon = 'plug-cloud.svg'
  [tile.button]
    link = '/'
    marker = 'warning'
    text = "TBD"

[[tile]]
  identifier = 'docbot'
  title = "<documentation bot>"
  text = "This is some explanatory text that is on two rows"
  icon = 'plug-cloud.svg'
  [tile.button]
    link = '/'
    marker = 'warning'
    text = "TBD"

[[tile]]
  identifier = 'gbot'
  title = "<drive bot>"
  text = "This is some explanatory text that is on two rows"
  icon = 'plug-cloud.svg'
  [tile.button]
    link = '/'
    marker = 'warning'
    text = "TBD"
+++

<!-- Additional content (not applicable for all widgets)-->
