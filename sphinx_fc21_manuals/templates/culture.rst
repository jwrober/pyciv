..
    SPDX-License-Identifier: GPL-3.0-or-later
    SPDX-FileCopyrightText: 2022 James Robertson <jwrober@gmail.com>

.. DO NOT EDIT THIS FILE MANUALLY. IT IS CREATED BY AN EXTERNAL AUTOMATED PROCESS. ANY CHANGES YOU MAKE CAN
.. BE OVERWRITTEN. YOU HAVE BEEN WARNED.

.. Custom Interpretive Text Roles for longturn.net/Freeciv21
.. role:: unit
.. role:: improvement
.. role:: wonder

Culture Victory Rules
=====================

{% if culture.victory_min_points %}
:strong:`Culture Victory Points` = {{ culture.victory_min_points }}
  {{ culture.victory_min_points_help_rst }}{% endif %}
{% if culture.victory_lead_pct %}
:strong:`Culture Victory Percentage Lead` = {{ culture.victory_lead_pct }}%
  {{ culture.victory_lead_pct_help_rst }}{% endif %}
{% if culture.history_interest_pml %}
:strong:`History Interest` = {{ culture.history_interest_pml }}
  {{ culture.history_interest_pml_help_rst }}{% endif %}
{% if culture.migration_pml %}
:strong:`Migration` = {{ culture.migration_pml }}
  {{ culture.migration_pml_help_rst }}{% endif %}
