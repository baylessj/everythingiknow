# Testing

never import a file with flutter/material or from lib into an integration, a 'dart:ui' error will appear

use keys everywhere as a result

loading indicators cause the driver to hang and not find objects even if they are present, because the test has effectively never settled.

