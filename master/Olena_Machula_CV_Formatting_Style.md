# CV Formatting Style Guide

Source: [Olena_Machula_CV_master](https://docs.google.com/document/d/130PuP8feSfTM03H6zOb8s6N2o5O8MyFvSJ9rkOkpzvg/edit)  
Extracted: 5 November 2026  
Scope: formatting specification, not a résumé content export.

## How to use this guide

Reproduce the explicitly applied formatting below when creating a Google Docs or Word résumé. Direct text and paragraph formatting takes precedence over stored named-style defaults. Markdown itself cannot enforce fonts, point sizes, page margins, columns, paragraph borders, or pagination; this file records those settings for use in a document editor.

## Page setup and sections

| Setting | Source value |
| --- | --- |
| Mode | Pages |
| Paper | A4 portrait: 595.2755905511812 × 841.8897637795277 pt (210 × 297 mm) |
| Document default margins | 72 pt on all sides |
| Section margins overriding document defaults | Top 30.95 pt; left and right 37.45 pt |
| Header and footer margins | 36 pt each |
| Text direction | Left to right |
| Column separator | None |
| Section transitions | Continuous |
| Header section | Two columns, each 230.199 pt; first-column gap 59.9775 pt; bottom margin 32.4 pt |
| Main body section | No explicit column array returned; single-column body indicated by section reset; bottom margin 31.972440944881953 pt |
| Education content section | Two columns, each 242.187 pt; first-column gap 36 pt; bottom margin 31.972440944881953 pt |

Units: 1 pt = 1/72 inch; millimetres = pt × 25.4 / 72. Point values above are authoritative. Rounded examples: top margin 30.95 × 25.4 / 72 = 10.92 mm; side margin 37.45 × 25.4 / 72 = 13.21 mm.

## Typography

| Element | Font | Size | Weight / treatment |
| --- | --- | --- | --- |
| Name | Raleway | 20 pt | Regular |
| Professional title | Raleway | 18 pt | Regular |
| Contact details and availability | Raleway | 11 pt | Regular |
| Summary | Raleway | 11 pt | Regular |
| Skills and Experience headings | Raleway | 15 pt | Regular, black |
| Education heading | Raleway | 16 pt | Regular, black |
| Skill category labels | Raleway | 11 pt | Bold |
| Skill descriptions | Raleway | 11 pt | Regular |
| Job title and company | Raleway | 13 pt | Bold, subject to exception below |
| Employment dates and location | Raleway | 12 pt | Bold |
| Experience bullet text | Raleway | 11 pt | Regular |
| University | Raleway | 12 pt | Bold |
| Degree lines | Raleway | 12 pt | Regular |
| Certification, Domains, Languages labels | Raleway | 11 pt | Bold |
| Certification, domain and language values | Raleway | 11 pt | Regular |

Raleway's returned font-family weight is 400; bold is applied through the separate bold property. Ordinary text inherits black (#000000) from the normal style. The section headings explicitly override the blue stored heading style with black.

## Paragraph layout

| Element | Alignment | Line spacing | Space before / after |
| --- | --- | --- | --- |
| Name | Start / left, inherited | 150% | 0 / 0 pt, inherited |
| Professional title | Start / left, inherited | 150% | 0 / 0 pt |
| Contact paragraphs | End / right | 150% | 0 / 0 pt |
| Summary | Justified | 125% | 0 / 0 pt |
| Section headings | Start / left, inherited | 115% | 8 / 8 pt |
| Skill category paragraphs | Justified | 115% | 6 / 6 pt |
| First job heading | Start / left, inherited | 150% | 4 / 2 pt |
| Later job headings | Start / left, inherited | 150% | 7 / 2 pt |
| Experience bullets | Justified | 150% | 0 / 0 pt, inherited |
| Education details | Start / left, inherited | 115% | 0 / 12 pt |

Line spacing percentages are paragraph line-spacing settings, not fixed point leading. Paragraph spacing uses NEVER_COLLAPSE where set directly or inherited from the normal style.

## Heading rules and dividers

- Skills, Experience, and Education use the semantic HEADING_2 style with direct visual overrides.
- Each section heading has a black solid bottom paragraph border: 1.5 pt wide, with 4 pt padding.
- Section headings have an end indent of 2.7 pt.
- Stored HEADING_2 defaults keep lines together and keep the heading with the next paragraph; Education also explicitly sets keepWithNext.
- The name and professional title are NORMAL_TEXT paragraphs with custom sizes, rather than TITLE or SUBTITLE styles.
- The summary has no separate visible section heading.

## Header structure and indents

- Put name and professional title in the first header column; contact details use end/right alignment.
- Phone and email share a paragraph separated by a soft line break.
- LinkedIn and availability share another paragraph separated by a soft line break.
- Name end indent: approximately 0.05 pt.
- Professional-title end indent: −10.825 pt.
- Contact paragraph end indent: 2.7 pt.
- LinkedIn/availability paragraph start and first-line indents: 21.259842519685023 pt.

## Experience structure and bullets

- A job heading combines the role/company line and date/location line in one paragraph, separated by a soft line break.
- Keep each job heading with the following paragraph.
- Use a solid round bullet: ● (Unicode U+25CF), list ID kix.list.1, level 0.
- List definition: bullet alignment START; first-line indent 21.259842519685044 pt; text start indent 0 pt.
- Each actual bullet paragraph also explicitly sets first-line indent 21.259842519685044 pt and end indent 2.7 pt.
- Preserve these unusual source indent values for literal reproduction; do not silently replace them with conventional hanging indents.
- Keep each bullet paragraph's lines together.
- Bullet glyph font in the list definition: Noto Sans Symbols, weight 400. Per-paragraph bullet text styles specify Raleway.
- Most bullet markers are 11 pt; the first two NearShorePartner.ch bullet markers are 10 pt, although their text remains 11 pt.
- Experience bullets in the source have no terminal full stops.

## Education and additional details

- Education is followed by a continuous two-column section.
- The education content is one paragraph using soft line breaks between the university, degree lines, certification, domains and languages.
- There are two soft line breaks before the Certification label.
- Keep the institution bold and degree values regular.
- Keep inline labels bold and their values regular.

## Source inconsistencies and reproduction limits

These are observed details, not suggested changes:

- Education is 16 pt while the other visible section headings are 15 pt.
- The first letter “Q” in the NearShorePartner.ch job title is 12 pt; the remaining title text is 13 pt.
- Two NearShorePartner.ch bullet markers are 10 pt rather than the usual 11 pt.
- The final NearShorePartner.ch bullet has a 12 pt paragraph-ending newline, although its visible text is 11 pt.
- The name's paragraph-ending newline is 11 pt rather than 20 pt.
- The Education heading ends with a bold 12 pt newline, although the visible heading is regular 16 pt.
- The first contact paragraph has an underlined paragraph-ending newline; its visible contact text does not explicitly set underline or a hyperlink.
- Tiny and negative end indents are preserved in the source.
- Stored named styles include Times New Roman and Calibri defaults; visible text explicitly uses Raleway.
- No headers, footers, inline objects or positioned objects were returned. No tables appear in the returned body.
- Page count, actual line wrapping, column flow and font rendering were not verified through a rendered export. A two-page limit is not inferred from formatting metadata.
- No additional colours, icons, backgrounds or graphics should be inferred from this specification.

## Complete formatting metadata

The following appendix preserves document defaults, named styles, list definitions, section properties and every paragraph/run formatting record returned by Google Docs. Text snippets identify the element; full résumé prose is intentionally omitted. Unused named styles and list definitions are retained for completeness and should not override the visible formatting above.

An absent property means it was not returned as a direct setting; consult the relevant named style or section inheritance. Empty Google API colour objects are preserved as returned. A populated rgbColor object with no channels represents black.

```json
{
  "documentStyle": {
    "background": {
      "color": {}
    },
    "pageNumberStart": 1,
    "marginTop": {
      "magnitude": 72,
      "unit": "PT"
    },
    "marginBottom": {
      "magnitude": 72,
      "unit": "PT"
    },
    "marginRight": {
      "magnitude": 72,
      "unit": "PT"
    },
    "marginLeft": {
      "magnitude": 72,
      "unit": "PT"
    },
    "pageSize": {
      "height": {
        "magnitude": 841.8897637795277,
        "unit": "PT"
      },
      "width": {
        "magnitude": 595.2755905511812,
        "unit": "PT"
      }
    },
    "marginHeader": {
      "magnitude": 36,
      "unit": "PT"
    },
    "marginFooter": {
      "magnitude": 36,
      "unit": "PT"
    },
    "useCustomHeaderFooterMargins": true,
    "documentFormat": {
      "documentMode": "PAGES"
    }
  },
  "namedStyles": {
    "styles": [
      {
        "namedStyleType": "NORMAL_TEXT",
        "textStyle": {
          "bold": false,
          "italic": false,
          "underline": false,
          "strikethrough": false,
          "smallCaps": false,
          "backgroundColor": {},
          "foregroundColor": {
            "color": {
              "rgbColor": {}
            }
          },
          "fontSize": {
            "magnitude": 10.5,
            "unit": "PT"
          },
          "weightedFontFamily": {
            "fontFamily": "Times New Roman",
            "weight": 400
          },
          "baselineOffset": "NONE"
        },
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "alignment": "START",
          "lineSpacing": 100,
          "direction": "LEFT_TO_RIGHT",
          "spacingMode": "NEVER_COLLAPSE",
          "spaceAbove": {
            "unit": "PT"
          },
          "spaceBelow": {
            "unit": "PT"
          },
          "borderBetween": {
            "color": {},
            "width": {
              "unit": "PT"
            },
            "padding": {
              "unit": "PT"
            },
            "dashStyle": "SOLID"
          },
          "borderTop": {
            "color": {},
            "width": {
              "unit": "PT"
            },
            "padding": {
              "unit": "PT"
            },
            "dashStyle": "SOLID"
          },
          "borderBottom": {
            "color": {},
            "width": {
              "unit": "PT"
            },
            "padding": {
              "unit": "PT"
            },
            "dashStyle": "SOLID"
          },
          "borderLeft": {
            "color": {},
            "width": {
              "unit": "PT"
            },
            "padding": {
              "unit": "PT"
            },
            "dashStyle": "SOLID"
          },
          "borderRight": {
            "color": {},
            "width": {
              "unit": "PT"
            },
            "padding": {
              "unit": "PT"
            },
            "dashStyle": "SOLID"
          },
          "indentFirstLine": {
            "unit": "PT"
          },
          "indentStart": {
            "unit": "PT"
          },
          "indentEnd": {
            "unit": "PT"
          },
          "keepLinesTogether": false,
          "keepWithNext": false,
          "avoidWidowAndOrphan": true,
          "shading": {
            "backgroundColor": {}
          },
          "pageBreakBefore": false
        }
      },
      {
        "namedStyleType": "HEADING_1",
        "textStyle": {
          "bold": true,
          "foregroundColor": {
            "color": {
              "rgbColor": {
                "red": 0.21176471,
                "green": 0.3764706,
                "blue": 0.5686275
              }
            }
          },
          "fontSize": {
            "magnitude": 14,
            "unit": "PT"
          },
          "weightedFontFamily": {
            "fontFamily": "Calibri",
            "weight": 400
          }
        },
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "direction": "LEFT_TO_RIGHT",
          "spaceAbove": {
            "magnitude": 24,
            "unit": "PT"
          },
          "keepLinesTogether": true,
          "keepWithNext": true
        }
      },
      {
        "namedStyleType": "HEADING_2",
        "textStyle": {
          "bold": true,
          "foregroundColor": {
            "color": {
              "rgbColor": {
                "red": 0.30980393,
                "green": 0.5058824,
                "blue": 0.7411765
              }
            }
          },
          "fontSize": {
            "magnitude": 13,
            "unit": "PT"
          },
          "weightedFontFamily": {
            "fontFamily": "Calibri",
            "weight": 400
          }
        },
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "direction": "LEFT_TO_RIGHT",
          "spaceAbove": {
            "magnitude": 10,
            "unit": "PT"
          },
          "keepLinesTogether": true,
          "keepWithNext": true
        }
      },
      {
        "namedStyleType": "HEADING_3",
        "textStyle": {
          "bold": true,
          "foregroundColor": {
            "color": {
              "rgbColor": {
                "red": 0.30980393,
                "green": 0.5058824,
                "blue": 0.7411765
              }
            }
          },
          "weightedFontFamily": {
            "fontFamily": "Calibri",
            "weight": 400
          }
        },
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "direction": "LEFT_TO_RIGHT",
          "spaceAbove": {
            "magnitude": 10,
            "unit": "PT"
          },
          "keepLinesTogether": true,
          "keepWithNext": true
        }
      },
      {
        "namedStyleType": "HEADING_4",
        "textStyle": {
          "bold": true,
          "italic": true,
          "foregroundColor": {
            "color": {
              "rgbColor": {
                "red": 0.30980393,
                "green": 0.5058824,
                "blue": 0.7411765
              }
            }
          },
          "weightedFontFamily": {
            "fontFamily": "Calibri",
            "weight": 400
          }
        },
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "direction": "LEFT_TO_RIGHT",
          "spaceAbove": {
            "magnitude": 10,
            "unit": "PT"
          },
          "keepLinesTogether": true,
          "keepWithNext": true
        }
      },
      {
        "namedStyleType": "HEADING_5",
        "textStyle": {
          "foregroundColor": {
            "color": {
              "rgbColor": {
                "red": 0.14117648,
                "green": 0.24705882,
                "blue": 0.38039216
              }
            }
          },
          "weightedFontFamily": {
            "fontFamily": "Calibri",
            "weight": 400
          }
        },
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "direction": "LEFT_TO_RIGHT",
          "spaceAbove": {
            "magnitude": 10,
            "unit": "PT"
          },
          "keepLinesTogether": true,
          "keepWithNext": true
        }
      },
      {
        "namedStyleType": "HEADING_6",
        "textStyle": {
          "italic": true,
          "foregroundColor": {
            "color": {
              "rgbColor": {
                "red": 0.14117648,
                "green": 0.24705882,
                "blue": 0.38039216
              }
            }
          },
          "weightedFontFamily": {
            "fontFamily": "Calibri",
            "weight": 400
          }
        },
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "direction": "LEFT_TO_RIGHT",
          "spaceAbove": {
            "magnitude": 10,
            "unit": "PT"
          },
          "keepLinesTogether": true,
          "keepWithNext": true
        }
      },
      {
        "namedStyleType": "TITLE",
        "textStyle": {
          "foregroundColor": {
            "color": {
              "rgbColor": {
                "red": 0.09019608,
                "green": 0.21176471,
                "blue": 0.3647059
              }
            }
          },
          "fontSize": {
            "magnitude": 26,
            "unit": "PT"
          },
          "weightedFontFamily": {
            "fontFamily": "Calibri",
            "weight": 400
          }
        },
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "direction": "LEFT_TO_RIGHT",
          "spacingMode": "NEVER_COLLAPSE",
          "spaceBelow": {
            "magnitude": 15,
            "unit": "PT"
          },
          "borderBottom": {
            "color": {
              "color": {
                "rgbColor": {
                  "red": 0.30980393,
                  "green": 0.5058824,
                  "blue": 0.7411765
                }
              }
            },
            "width": {
              "magnitude": 1,
              "unit": "PT"
            },
            "padding": {
              "magnitude": 4,
              "unit": "PT"
            },
            "dashStyle": "SOLID"
          }
        }
      },
      {
        "namedStyleType": "SUBTITLE",
        "textStyle": {
          "italic": true,
          "foregroundColor": {
            "color": {
              "rgbColor": {
                "red": 0.30980393,
                "green": 0.5058824,
                "blue": 0.7411765
              }
            }
          },
          "fontSize": {
            "magnitude": 12,
            "unit": "PT"
          },
          "weightedFontFamily": {
            "fontFamily": "Calibri",
            "weight": 400
          }
        },
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "direction": "LEFT_TO_RIGHT"
        }
      }
    ]
  },
  "lists": {
    "kix.list.1": {
      "listProperties": {
        "nestingLevels": [
          {
            "bulletAlignment": "START",
            "glyphSymbol": "●",
            "glyphFormat": "%0",
            "indentFirstLine": {
              "magnitude": 21.259842519685044,
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {
              "weightedFontFamily": {
                "fontFamily": "Noto Sans Symbols",
                "weight": 400
              }
            },
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          }
        ]
      }
    },
    "kix.list.2": {
      "listProperties": {
        "nestingLevels": [
          {
            "bulletAlignment": "START",
            "glyphSymbol": "●",
            "glyphFormat": "%0",
            "indentFirstLine": {
              "magnitude": 18,
              "unit": "PT"
            },
            "indentStart": {
              "magnitude": 36,
              "unit": "PT"
            },
            "textStyle": {
              "weightedFontFamily": {
                "fontFamily": "Noto Sans Symbols",
                "weight": 400
              }
            },
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          }
        ]
      }
    },
    "kix.list.3": {
      "listProperties": {
        "nestingLevels": [
          {
            "bulletAlignment": "START",
            "glyphSymbol": "●",
            "glyphFormat": "%0",
            "indentFirstLine": {
              "magnitude": 36,
              "unit": "PT"
            },
            "indentStart": {
              "magnitude": 54,
              "unit": "PT"
            },
            "textStyle": {
              "weightedFontFamily": {
                "fontFamily": "Noto Sans Symbols",
                "weight": 400
              }
            },
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          }
        ]
      }
    },
    "kix.list.4": {
      "listProperties": {
        "nestingLevels": [
          {
            "bulletAlignment": "START",
            "glyphSymbol": "●",
            "glyphFormat": "%0",
            "indentFirstLine": {
              "magnitude": 54,
              "unit": "PT"
            },
            "indentStart": {
              "magnitude": 72,
              "unit": "PT"
            },
            "textStyle": {
              "weightedFontFamily": {
                "fontFamily": "Noto Sans Symbols",
                "weight": 400
              }
            },
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          }
        ]
      }
    },
    "kix.list.5": {
      "listProperties": {
        "nestingLevels": [
          {
            "bulletAlignment": "START",
            "glyphType": "DECIMAL",
            "glyphFormat": "%0.",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "magnitude": 18,
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          }
        ]
      }
    },
    "kix.list.6": {
      "listProperties": {
        "nestingLevels": [
          {
            "bulletAlignment": "START",
            "glyphType": "DECIMAL",
            "glyphFormat": "%0.",
            "indentFirstLine": {
              "magnitude": 18,
              "unit": "PT"
            },
            "indentStart": {
              "magnitude": 36,
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          }
        ]
      }
    },
    "kix.list.7": {
      "listProperties": {
        "nestingLevels": [
          {
            "bulletAlignment": "START",
            "glyphType": "DECIMAL",
            "glyphFormat": "%0.",
            "indentFirstLine": {
              "magnitude": 36,
              "unit": "PT"
            },
            "indentStart": {
              "magnitude": 54,
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          }
        ]
      }
    },
    "kix.list.8": {
      "listProperties": {
        "nestingLevels": [
          {
            "bulletAlignment": "START",
            "glyphType": "DECIMAL",
            "glyphFormat": "%0.",
            "indentFirstLine": {
              "magnitude": 54,
              "unit": "PT"
            },
            "indentStart": {
              "magnitude": 72,
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          }
        ]
      }
    },
    "kix.list.9": {
      "listProperties": {
        "nestingLevels": [
          {
            "bulletAlignment": "START",
            "glyphType": "DECIMAL",
            "glyphFormat": "%0.",
            "indentFirstLine": {
              "magnitude": 72,
              "unit": "PT"
            },
            "indentStart": {
              "magnitude": 90,
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          },
          {
            "bulletAlignment": "START",
            "glyphType": "NONE",
            "indentFirstLine": {
              "unit": "PT"
            },
            "indentStart": {
              "unit": "PT"
            },
            "textStyle": {},
            "startNumber": 1
          }
        ]
      }
    }
  },
  "formattingRecords": [
    {
      "startIndex": 0,
      "endIndex": 1,
      "sectionBreak": {
        "sectionStyle": {
          "columnProperties": [
            {
              "width": {
                "magnitude": 230.199,
                "unit": "PT"
              },
              "paddingEnd": {
                "magnitude": 59.9775,
                "unit": "PT"
              }
            },
            {
              "width": {
                "magnitude": 230.199,
                "unit": "PT"
              },
              "paddingEnd": {
                "unit": "PT"
              }
            }
          ],
          "columnSeparatorStyle": "NONE",
          "contentDirection": "LEFT_TO_RIGHT",
          "marginTop": {
            "magnitude": 30.95,
            "unit": "PT"
          },
          "marginBottom": {
            "magnitude": 32.4,
            "unit": "PT"
          },
          "marginRight": {
            "magnitude": 37.45,
            "unit": "PT"
          },
          "marginLeft": {
            "magnitude": 37.45,
            "unit": "PT"
          },
          "marginHeader": {
            "magnitude": 36,
            "unit": "PT"
          },
          "marginFooter": {
            "magnitude": 36,
            "unit": "PT"
          },
          "sectionType": "CONTINUOUS"
        }
      }
    },
    {
      "startIndex": 1,
      "endIndex": 15,
      "paragraph": {
        "label": "Olena Machula",
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "lineSpacing": 150,
          "direction": "LEFT_TO_RIGHT",
          "indentEnd": {
            "magnitude": 0.04999999999999716,
            "unit": "PT"
          }
        },
        "runs": [
          {
            "startIndex": 1,
            "endIndex": 14,
            "textPreview": "Olena Machula",
            "textStyle": {
              "fontSize": {
                "magnitude": 20,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          },
          {
            "startIndex": 14,
            "endIndex": 15,
            "textPreview": "\n",
            "textStyle": {
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          }
        ]
      }
    },
    {
      "startIndex": 15,
      "endIndex": 59,
      "paragraph": {
        "label": "Lead QA | Senior Quality Assurance Engineer",
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "lineSpacing": 150,
          "direction": "LEFT_TO_RIGHT",
          "spacingMode": "NEVER_COLLAPSE",
          "spaceAbove": {
            "unit": "PT"
          },
          "spaceBelow": {
            "unit": "PT"
          },
          "indentEnd": {
            "magnitude": -10.825000000000003,
            "unit": "PT"
          }
        },
        "runs": [
          {
            "startIndex": 15,
            "endIndex": 59,
            "textPreview": "Lead QA | Senior Quality Assurance Engineer\n",
            "textStyle": {
              "fontSize": {
                "magnitude": 18,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          }
        ]
      }
    },
    {
      "startIndex": 59,
      "endIndex": 100,
      "paragraph": {
        "label": "+380 99 139 73 67\u000bchagovets.xx@gmail.com",
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "alignment": "END",
          "lineSpacing": 150,
          "direction": "LEFT_TO_RIGHT",
          "spacingMode": "NEVER_COLLAPSE",
          "spaceAbove": {
            "unit": "PT"
          },
          "spaceBelow": {
            "unit": "PT"
          },
          "indentEnd": {
            "magnitude": 2.7,
            "unit": "PT"
          }
        },
        "runs": [
          {
            "startIndex": 59,
            "endIndex": 99,
            "textPreview": "+380 99 139 73 67\u000bchagovets.xx@gmail.com",
            "textStyle": {
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          },
          {
            "startIndex": 99,
            "endIndex": 100,
            "textPreview": "\n",
            "textStyle": {
              "underline": true,
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          }
        ]
      }
    },
    {
      "startIndex": 100,
      "endIndex": 170,
      "paragraph": {
        "label": "linkedin.com/in/olena-machula\u000bRemote | Open to EU / UK opportunities",
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "alignment": "END",
          "lineSpacing": 150,
          "direction": "LEFT_TO_RIGHT",
          "spacingMode": "NEVER_COLLAPSE",
          "spaceAbove": {
            "unit": "PT"
          },
          "spaceBelow": {
            "unit": "PT"
          },
          "indentFirstLine": {
            "magnitude": 21.259842519685023,
            "unit": "PT"
          },
          "indentStart": {
            "magnitude": 21.259842519685023,
            "unit": "PT"
          },
          "indentEnd": {
            "magnitude": 2.7,
            "unit": "PT"
          }
        },
        "runs": [
          {
            "startIndex": 100,
            "endIndex": 170,
            "textPreview": "linkedin.com/in/olena-machula\u000bRemote | Open to EU / UK opportunities \n",
            "textStyle": {
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          }
        ]
      }
    },
    {
      "startIndex": 170,
      "endIndex": 171,
      "sectionBreak": {
        "sectionStyle": {
          "columnSeparatorStyle": "NONE",
          "contentDirection": "LEFT_TO_RIGHT",
          "marginTop": {
            "magnitude": 30.95,
            "unit": "PT"
          },
          "marginBottom": {
            "magnitude": 31.972440944881953,
            "unit": "PT"
          },
          "marginRight": {
            "magnitude": 37.45,
            "unit": "PT"
          },
          "marginLeft": {
            "magnitude": 37.45,
            "unit": "PT"
          },
          "marginHeader": {
            "magnitude": 36,
            "unit": "PT"
          },
          "marginFooter": {
            "magnitude": 36,
            "unit": "PT"
          },
          "sectionType": "CONTINUOUS",
          "useFirstPageHeaderFooter": false,
          "flipPageOrientation": false
        }
      }
    },
    {
      "startIndex": 171,
      "endIndex": 709,
      "paragraph": {
        "label": "QA Lead with 7+ years of software quality assurance experience and 3 years leading a team ",
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "alignment": "JUSTIFIED",
          "lineSpacing": 125,
          "direction": "LEFT_TO_RIGHT",
          "spacingMode": "NEVER_COLLAPSE",
          "spaceAbove": {
            "unit": "PT"
          },
          "spaceBelow": {
            "unit": "PT"
          }
        },
        "runs": [
          {
            "startIndex": 171,
            "endIndex": 708,
            "textPreview": "QA Lead with 7+ years of software quality assurance experience and 3 y",
            "textStyle": {
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          },
          {
            "startIndex": 708,
            "endIndex": 709,
            "textPreview": "\n",
            "textStyle": {
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          }
        ]
      }
    },
    {
      "startIndex": 709,
      "endIndex": 716,
      "paragraph": {
        "label": "Skills",
        "paragraphStyle": {
          "headingId": "h.tfyvcbtlxmfz",
          "namedStyleType": "HEADING_2",
          "lineSpacing": 115,
          "direction": "LEFT_TO_RIGHT",
          "spaceAbove": {
            "magnitude": 8,
            "unit": "PT"
          },
          "spaceBelow": {
            "magnitude": 8,
            "unit": "PT"
          },
          "borderBottom": {
            "color": {
              "color": {
                "rgbColor": {}
              }
            },
            "width": {
              "magnitude": 1.5,
              "unit": "PT"
            },
            "padding": {
              "magnitude": 4,
              "unit": "PT"
            },
            "dashStyle": "SOLID"
          },
          "indentEnd": {
            "magnitude": 2.7,
            "unit": "PT"
          }
        },
        "runs": [
          {
            "startIndex": 709,
            "endIndex": 716,            "textPreview": "Skills\n",
            "textStyle": {
              "bold": false,
              "foregroundColor": {
                "color": {
                  "rgbColor": {}
                }
              },
              "fontSize": {
                "magnitude": 15,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          }
        ]
      }
    },
    {
      "startIndex": 716,
      "endIndex": 933,
      "paragraph": {
        "label": "QA Leadership & Strategy: QA Leadership, QA Strategy, Test Strategy, Quality Management, T",
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "alignment": "JUSTIFIED",
          "lineSpacing": 115,
          "direction": "LEFT_TO_RIGHT",
          "spacingMode": "NEVER_COLLAPSE",
          "spaceAbove": {
            "magnitude": 6,
            "unit": "PT"
          },
          "spaceBelow": {
            "magnitude": 6,
            "unit": "PT"
          }
        },
        "runs": [
          {
            "startIndex": 716,
            "endIndex": 741,
            "textPreview": "QA Leadership & Strategy:",
            "textStyle": {
              "bold": true,
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          },
          {
            "startIndex": 741,
            "endIndex": 933,
            "textPreview": " QA Leadership, QA Strategy, Test Strategy, Quality Management, Test P",
            "textStyle": {
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          }
        ]
      }
    },
    {
      "startIndex": 933,
      "endIndex": 1122,
      "paragraph": {
        "label": "Release & Quality Ownership: Release Management, Release Validation, Release Readiness, Qu",
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "alignment": "JUSTIFIED",
          "lineSpacing": 115,
          "direction": "LEFT_TO_RIGHT",
          "spacingMode": "NEVER_COLLAPSE",
          "spaceAbove": {
            "magnitude": 6,
            "unit": "PT"
          },
          "spaceBelow": {
            "magnitude": 6,
            "unit": "PT"
          }
        },
        "runs": [
          {
            "startIndex": 933,
            "endIndex": 961,
            "textPreview": "Release & Quality Ownership:",
            "textStyle": {
              "bold": true,
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          },
          {
            "startIndex": 961,
            "endIndex": 1122,
            "textPreview": " Release Management, Release Validation, Release Readiness, Quality Ga",
            "textStyle": {
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          }
        ]
      }
    },
    {
      "startIndex": 1122,
      "endIndex": 1294,
      "paragraph": {
        "label": "Test Management & Analysis: Requirements Analysis, Test Design, Test Coverage Analysis, Te",
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "alignment": "JUSTIFIED",
          "lineSpacing": 115,
          "direction": "LEFT_TO_RIGHT",
          "spacingMode": "NEVER_COLLAPSE",
          "spaceAbove": {
            "magnitude": 6,
            "unit": "PT"
          },
          "spaceBelow": {
            "magnitude": 6,
            "unit": "PT"
          }
        },
        "runs": [
          {
            "startIndex": 1122,
            "endIndex": 1149,
            "textPreview": "Test Management & Analysis:",
            "textStyle": {
              "bold": true,
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          },
          {
            "startIndex": 1149,
            "endIndex": 1294,
            "textPreview": " Requirements Analysis, Test Design, Test Coverage Analysis, Test Case",
            "textStyle": {
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          }
        ]
      }
    },
    {
      "startIndex": 1294,
      "endIndex": 1445,
      "paragraph": {
        "label": "API & Backend: REST API Testing, API Integration Testing, HTTP/HTTPS, Postman, Swagger/Ope",
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "alignment": "JUSTIFIED",
          "lineSpacing": 115,
          "direction": "LEFT_TO_RIGHT",
          "spacingMode": "NEVER_COLLAPSE",
          "spaceAbove": {
            "magnitude": 6,
            "unit": "PT"
          },
          "spaceBelow": {
            "magnitude": 6,
            "unit": "PT"
          }
        },
        "runs": [
          {
            "startIndex": 1294,
            "endIndex": 1308,
            "textPreview": "API & Backend:",
            "textStyle": {
              "bold": true,
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          },
          {
            "startIndex": 1308,
            "endIndex": 1445,
            "textPreview": " REST API Testing, API Integration Testing, HTTP/HTTPS, Postman, Swagg",
            "textStyle": {
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          }
        ]
      }
    },
    {
      "startIndex": 1445,
      "endIndex": 1612,
      "paragraph": {
        "label": "Automation & Quality Engineering: Quality Engineering, Test Automation Strategy, Automatio",
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "alignment": "JUSTIFIED",
          "lineSpacing": 115,
          "direction": "LEFT_TO_RIGHT",
          "spacingMode": "NEVER_COLLAPSE",
          "spaceAbove": {
            "magnitude": 6,
            "unit": "PT"
          },
          "spaceBelow": {
            "magnitude": 6,
            "unit": "PT"
          }
        },
        "runs": [
          {
            "startIndex": 1445,
            "endIndex": 1478,
            "textPreview": "Automation & Quality Engineering:",
            "textStyle": {
              "bold": true,
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          },
          {
            "startIndex": 1478,
            "endIndex": 1612,
            "textPreview": " Quality Engineering, Test Automation Strategy, Automation Coverage Pl",
            "textStyle": {
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          }
        ]
      }
    },
    {
      "startIndex": 1612,
      "endIndex": 1820,
      "paragraph": {
        "label": "Leadership & Collaboration: QA Team Leadership, Mentoring, Cross-functional Collaboration,",
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "alignment": "JUSTIFIED",
          "lineSpacing": 115,
          "direction": "LEFT_TO_RIGHT",
          "spacingMode": "NEVER_COLLAPSE",
          "spaceAbove": {
            "magnitude": 6,
            "unit": "PT"
          },
          "spaceBelow": {
            "magnitude": 6,
            "unit": "PT"
          }
        },
        "runs": [
          {
            "startIndex": 1612,
            "endIndex": 1639,
            "textPreview": "Leadership & Collaboration:",
            "textStyle": {
              "bold": true,
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          },
          {
            "startIndex": 1639,
            "endIndex": 1820,
            "textPreview": " QA Team Leadership, Mentoring, Cross-functional Collaboration, Stakeh",
            "textStyle": {
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          }
        ]
      }
    },
    {
      "startIndex": 1820,
      "endIndex": 1831,
      "paragraph": {
        "label": "Experience",
        "paragraphStyle": {
          "headingId": "h.nhzx5a2zte71",
          "namedStyleType": "HEADING_2",
          "lineSpacing": 115,
          "direction": "LEFT_TO_RIGHT",
          "spaceAbove": {
            "magnitude": 8,
            "unit": "PT"
          },
          "spaceBelow": {
            "magnitude": 8,
            "unit": "PT"
          },
          "borderBottom": {
            "color": {
              "color": {
                "rgbColor": {}
              }
            },
            "width": {
              "magnitude": 1.5,
              "unit": "PT"
            },
            "padding": {
              "magnitude": 4,
              "unit": "PT"
            },
            "dashStyle": "SOLID"
          },
          "indentEnd": {
            "magnitude": 2.7,
            "unit": "PT"
          }
        },
        "runs": [
          {
            "startIndex": 1820,
            "endIndex": 1831,
            "textPreview": "Experience\n",
            "textStyle": {
              "bold": false,
              "foregroundColor": {
                "color": {
                  "rgbColor": {}
                }
              },
              "fontSize": {
                "magnitude": 15,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          }
        ]
      }
    },
    {
      "startIndex": 1831,
      "endIndex": 1926,
      "paragraph": {
        "label": "QA Lead / Senior Quality Assurance Engineer | Möbel Pfister AG\u000bApril 2023 – July 2026 | Re",
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "lineSpacing": 150,
          "direction": "LEFT_TO_RIGHT",
          "spaceAbove": {
            "magnitude": 4,
            "unit": "PT"
          },
          "spaceBelow": {
            "magnitude": 2,
            "unit": "PT"
          },
          "indentEnd": {
            "magnitude": 2.7,
            "unit": "PT"
          },
          "keepWithNext": true
        },
        "runs": [
          {
            "startIndex": 1831,
            "endIndex": 1893,
            "textPreview": "QA Lead / Senior Quality Assurance Engineer | Möbel Pfister AG",
            "textStyle": {
              "bold": true,
              "fontSize": {
                "magnitude": 13,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          },
          {
            "startIndex": 1893,
            "endIndex": 1925,
            "textPreview": "\u000bApril 2023 – July 2026 | Remote",
            "textStyle": {
              "bold": true,
              "fontSize": {
                "magnitude": 12,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          },
          {
            "startIndex": 1925,
            "endIndex": 1926,
            "textPreview": "\n",
            "textStyle": {
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          }
        ]
      }
    },
    {
      "startIndex": 1926,
      "endIndex": 2150,
      "paragraph": {
        "label": "Led quality delivery across 2 interconnected systems and 4–5 production releases per month",
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "alignment": "JUSTIFIED",
          "lineSpacing": 150,
          "direction": "LEFT_TO_RIGHT",
          "indentFirstLine": {
            "magnitude": 21.259842519685044,
            "unit": "PT"
          },
          "indentEnd": {
            "magnitude": 2.7,
            "unit": "PT"
          },
          "keepLinesTogether": true
        },
        "bullet": {
          "listId": "kix.list.1",
          "textStyle": {
            "fontSize": {
              "magnitude": 11,
              "unit": "PT"
            },
            "weightedFontFamily": {
              "fontFamily": "Raleway",
              "weight": 400
            }
          }
        },
        "runs": [
          {
            "startIndex": 1926,
            "endIndex": 2150,
            "textPreview": "Led quality delivery across 2 interconnected systems and 4–5 productio",
            "textStyle": {
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          }
        ]
      }
    },
    {
      "startIndex": 2150,
      "endIndex": 2281,
      "paragraph": {
        "label": "Managed and developed a 5-person QA team through goal setting, 1:1s, performance reviews, ",
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "alignment": "JUSTIFIED",
          "lineSpacing": 150,
          "direction": "LEFT_TO_RIGHT",
          "indentFirstLine": {
            "magnitude": 21.259842519685044,
            "unit": "PT"
          },
          "indentEnd": {
            "magnitude": 2.7,
            "unit": "PT"
          },
          "keepLinesTogether": true
        },
        "bullet": {
          "listId": "kix.list.1",
          "textStyle": {
            "fontSize": {
              "magnitude": 11,
              "unit": "PT"
            },
            "weightedFontFamily": {
              "fontFamily": "Raleway",
              "weight": 400
            }
          }
        },
        "runs": [
          {
            "startIndex": 2150,
            "endIndex": 2281,
            "textPreview": "Managed and developed a 5-person QA team through goal setting, 1:1s, p",
            "textStyle": {
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          }
        ]
      }
    },
    {
      "startIndex": 2281,
      "endIndex": 2477,
      "paragraph": {
        "label": "Reduced late discovery of quality risks by applying shift-left testing during requirements",
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "alignment": "JUSTIFIED",
          "lineSpacing": 150,
          "direction": "LEFT_TO_RIGHT",
          "indentFirstLine": {
            "magnitude": 21.259842519685044,
            "unit": "PT"
          },
          "indentEnd": {
            "magnitude": 2.7,
            "unit": "PT"
          },
          "keepLinesTogether": true
        },
        "bullet": {
          "listId": "kix.list.1",
          "textStyle": {
            "fontSize": {
              "magnitude": 11,
              "unit": "PT"
            },
            "weightedFontFamily": {
              "fontFamily": "Raleway",
              "weight": 400
            }
          }
        },
        "runs": [
          {
            "startIndex": 2281,
            "endIndex": 2477,
            "textPreview": "Reduced late discovery of quality risks by applying shift-left testing",
            "textStyle": {
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          }
        ]
      }
    },
    {
      "startIndex": 2477,
      "endIndex": 2744,
      "paragraph": {
        "label": "Increased automated regression protection for business-critical web functionality by devel",
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "alignment": "JUSTIFIED",
          "lineSpacing": 150,
          "direction": "LEFT_TO_RIGHT",
          "indentFirstLine": {
            "magnitude": 21.259842519685044,
            "unit": "PT"
          },
          "indentEnd": {
            "magnitude": 2.7,
            "unit": "PT"
          },
          "keepLinesTogether": true
        },
        "bullet": {
          "listId": "kix.list.1",
          "textStyle": {
            "fontSize": {
              "magnitude": 11,
              "unit": "PT"
            },
            "weightedFontFamily": {
              "fontFamily": "Raleway",
              "weight": 400
            }
          }
        },
        "runs": [
          {
            "startIndex": 2477,
            "endIndex": 2744,
            "textPreview": "Increased automated regression protection for business-critical web fu",
            "textStyle": {
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          }
        ]
      }
    },
    {
      "startIndex": 2744,
      "endIndex": 2941,
      "paragraph": {
        "label": "Protected business-critical workflows across payment integrations, REST APIs, asynchronous",
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "alignment": "JUSTIFIED",
          "lineSpacing": 150,
          "direction": "LEFT_TO_RIGHT",
          "indentFirstLine": {
            "magnitude": 21.259842519685044,
            "unit": "PT"
          },
          "indentEnd": {
            "magnitude": 2.7,
            "unit": "PT"
          },
          "keepLinesTogether": true
        },
        "bullet": {
          "listId": "kix.list.1",
          "textStyle": {
            "fontSize": {
              "magnitude": 11,
              "unit": "PT"
            },
            "weightedFontFamily": {
              "fontFamily": "Raleway",
              "weight": 400
            }
          }
        },
        "runs": [
          {
            "startIndex": 2744,
            "endIndex": 2941,
            "textPreview": "Protected business-critical workflows across payment integrations, RES",
            "textStyle": {
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          }
        ]
      }
    },
    {
      "startIndex": 2941,
      "endIndex": 3134,
      "paragraph": {
        "label": "Increased automated regression protection for business-critical functionality by defining ",
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "alignment": "JUSTIFIED",
          "lineSpacing": 150,
          "direction": "LEFT_TO_RIGHT",
          "indentFirstLine": {
            "magnitude": 21.259842519685044,
            "unit": "PT"
          },
          "indentEnd": {
            "magnitude": 2.7,
            "unit": "PT"
          },
          "keepLinesTogether": true
        },
        "bullet": {
          "listId": "kix.list.1",
          "textStyle": {
            "fontSize": {
              "magnitude": 11,
              "unit": "PT"
            },
            "weightedFontFamily": {
              "fontFamily": "Raleway",
              "weight": 400
            }
          }
        },
        "runs": [
          {
            "startIndex": 2941,
            "endIndex": 3134,
            "textPreview": "Increased automated regression protection for business-critical functi",
            "textStyle": {
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          }
        ]
      }
    },
    {
      "startIndex": 3134,
      "endIndex": 3363,
      "paragraph": {
        "label": "Improved QA workflows across requirement analysis, test case design, and bug reporting by ",
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "alignment": "JUSTIFIED",
          "lineSpacing": 150,
          "direction": "LEFT_TO_RIGHT",
          "indentFirstLine": {
            "magnitude": 21.259842519685044,
            "unit": "PT"
          },
          "indentEnd": {
            "magnitude": 2.7,
            "unit": "PT"
          },
          "keepLinesTogether": true
        },
        "bullet": {
          "listId": "kix.list.1",
          "textStyle": {
            "fontSize": {
              "magnitude": 11,
              "unit": "PT"
            },
            "weightedFontFamily": {
              "fontFamily": "Raleway",
              "weight": 400
            }
          }
        },
        "runs": [
          {
            "startIndex": 3134,
            "endIndex": 3363,
            "textPreview": "Improved QA workflows across requirement analysis, test case design, a",
            "textStyle": {
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          }
        ]
      }
    },
    {
      "startIndex": 3363,
      "endIndex": 3447,
      "paragraph": {
        "label": "Quality Assurance Engineer | MobiDev\u000bSeptember 2021 – March 2023 | Kharkiv, Ukraine",
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "lineSpacing": 150,
          "direction": "LEFT_TO_RIGHT",
          "spaceAbove": {
            "magnitude": 7,
            "unit": "PT"
          },
          "spaceBelow": {
            "magnitude": 2,
            "unit": "PT"
          },
          "indentEnd": {
            "magnitude": 2.7,
            "unit": "PT"
          },
          "keepWithNext": true
        },
        "runs": [
          {
            "startIndex": 3363,
            "endIndex": 3399,
            "textPreview": "Quality Assurance Engineer | MobiDev",
            "textStyle": {
              "bold": true,
              "fontSize": {
                "magnitude": 13,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          },
          {
            "startIndex": 3399,
            "endIndex": 3446,
            "textPreview": "\u000bSeptember 2021 – March 2023 | Kharkiv, Ukraine",
            "textStyle": {
              "bold": true,
              "fontSize": {
                "magnitude": 12,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          },
          {
            "startIndex": 3446,
            "endIndex": 3447,
            "textPreview": "\n",
            "textStyle": {
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          }
        ]
      }
    },
    {
      "startIndex": 3447,
      "endIndex": 3634,
      "paragraph": {
        "label": "Improved early defect detection by applying shift-left testing during requirements analysi",
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "alignment": "JUSTIFIED",
          "lineSpacing": 150,
          "direction": "LEFT_TO_RIGHT",
          "indentFirstLine": {
            "magnitude": 21.259842519685044,
            "unit": "PT"
          },
          "indentEnd": {
            "magnitude": 2.7,
            "unit": "PT"
          },
          "keepLinesTogether": true
        },
        "bullet": {
          "listId": "kix.list.1",
          "textStyle": {
            "fontSize": {
              "magnitude": 11,
              "unit": "PT"
            },
            "weightedFontFamily": {
              "fontFamily": "Raleway",
              "weight": 400
            }
          }
        },
        "runs": [
          {
            "startIndex": 3447,
            "endIndex": 3634,
            "textPreview": "Improved early defect detection by applying shift-left testing during ",
            "textStyle": {
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          }
        ]
      }
    },
    {
      "startIndex": 3634,
      "endIndex": 3850,
      "paragraph": {
        "label": "Increased confidence in data consistency across 2 interconnected systems by testing cross-",
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "alignment": "JUSTIFIED",
          "lineSpacing": 150,
          "direction": "LEFT_TO_RIGHT",
          "indentFirstLine": {
            "magnitude": 21.259842519685044,
            "unit": "PT"
          },
          "indentEnd": {
            "magnitude": 2.7,
            "unit": "PT"
          },
          "keepLinesTogether": true
        },
        "bullet": {          "listId": "kix.list.1",
          "textStyle": {
            "fontSize": {
              "magnitude": 11,
              "unit": "PT"
            },
            "weightedFontFamily": {
              "fontFamily": "Raleway",
              "weight": 400
            }
          }
        },
        "runs": [
          {
            "startIndex": 3634,
            "endIndex": 3850,
            "textPreview": "Increased confidence in data consistency across 2 interconnected syste",
            "textStyle": {
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          }
        ]
      }
    },
    {
      "startIndex": 3850,
      "endIndex": 4030,
      "paragraph": {
        "label": "Strengthened integration coverage by validating positive, negative, duplicate, delayed, an",
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "alignment": "JUSTIFIED",
          "lineSpacing": 150,
          "direction": "LEFT_TO_RIGHT",
          "indentFirstLine": {
            "magnitude": 21.259842519685044,
            "unit": "PT"
          },
          "indentEnd": {
            "magnitude": 2.7,
            "unit": "PT"
          },
          "keepLinesTogether": true
        },
        "bullet": {
          "listId": "kix.list.1",
          "textStyle": {
            "fontSize": {
              "magnitude": 11,
              "unit": "PT"
            },
            "weightedFontFamily": {
              "fontFamily": "Raleway",
              "weight": 400
            }
          }
        },
        "runs": [
          {
            "startIndex": 3850,
            "endIndex": 4030,
            "textPreview": "Strengthened integration coverage by validating positive, negative, du",
            "textStyle": {
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          }
        ]
      }
    },
    {
      "startIndex": 4030,
      "endIndex": 4227,
      "paragraph": {
        "label": "Improved product quality across web, Android, and iOS applications by executing functional",
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "alignment": "JUSTIFIED",
          "lineSpacing": 150,
          "direction": "LEFT_TO_RIGHT",
          "indentFirstLine": {
            "magnitude": 21.259842519685044,
            "unit": "PT"
          },
          "indentEnd": {
            "magnitude": 2.7,
            "unit": "PT"
          },
          "keepLinesTogether": true
        },
        "bullet": {
          "listId": "kix.list.1",
          "textStyle": {
            "fontSize": {
              "magnitude": 11,
              "unit": "PT"
            },
            "weightedFontFamily": {
              "fontFamily": "Raleway",
              "weight": 400
            }
          }
        },
        "runs": [
          {
            "startIndex": 4030,
            "endIndex": 4227,
            "textPreview": "Improved product quality across web, Android, and iOS applications by ",
            "textStyle": {
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          }
        ]
      }
    },
    {
      "startIndex": 4227,
      "endIndex": 4441,
      "paragraph": {
        "label": "Reduced investigation time for critical defects by analysing API behaviour, browser DevToo",
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "alignment": "JUSTIFIED",
          "lineSpacing": 150,
          "direction": "LEFT_TO_RIGHT",
          "indentFirstLine": {
            "magnitude": 21.259842519685044,
            "unit": "PT"
          },
          "indentEnd": {
            "magnitude": 2.7,
            "unit": "PT"
          },
          "keepLinesTogether": true
        },
        "bullet": {
          "listId": "kix.list.1",
          "textStyle": {
            "fontSize": {
              "magnitude": 11,
              "unit": "PT"
            },
            "weightedFontFamily": {
              "fontFamily": "Raleway",
              "weight": 400
            }
          }
        },
        "runs": [
          {
            "startIndex": 4227,
            "endIndex": 4440,
            "textPreview": "Reduced investigation time for critical defects by analysing API behav",
            "textStyle": {
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          },
          {
            "startIndex": 4440,
            "endIndex": 4441,
            "textPreview": "\n",
            "textStyle": {
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          }
        ]
      }
    },
    {
      "startIndex": 4441,
      "endIndex": 4537,
      "paragraph": {
        "label": "Quality Assurance Engineer | NearShorePartner.ch\u000bFebruary 2019 – August 2021 | Kharkiv, Uk",
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "lineSpacing": 150,
          "direction": "LEFT_TO_RIGHT",
          "spaceAbove": {
            "magnitude": 7,
            "unit": "PT"
          },
          "spaceBelow": {
            "magnitude": 2,
            "unit": "PT"
          },
          "indentEnd": {
            "magnitude": 2.7,
            "unit": "PT"
          },
          "keepWithNext": true
        },
        "runs": [
          {
            "startIndex": 4441,
            "endIndex": 4442,
            "textPreview": "Q",
            "textStyle": {
              "bold": true,
              "fontSize": {
                "magnitude": 12,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          },
          {
            "startIndex": 4442,
            "endIndex": 4470,
            "textPreview": "uality Assurance Engineer | ",
            "textStyle": {
              "bold": true,
              "fontSize": {
                "magnitude": 13,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          },
          {
            "startIndex": 4470,
            "endIndex": 4490,
            "textPreview": "NearShorePartner.ch\u000b",
            "textStyle": {
              "bold": true,
              "fontSize": {
                "magnitude": 13,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          },
          {
            "startIndex": 4490,
            "endIndex": 4537,
            "textPreview": "February 2019 – August 2021 | Kharkiv, Ukraine\n",
            "textStyle": {
              "bold": true,
              "fontSize": {
                "magnitude": 12,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          }
        ]
      }
    },
    {
      "startIndex": 4537,
      "endIndex": 4711,
      "paragraph": {
        "label": "Improved product quality across web and mobile applications by executing functional, non-f",
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "alignment": "JUSTIFIED",
          "lineSpacing": 150,
          "direction": "LEFT_TO_RIGHT",
          "indentFirstLine": {
            "magnitude": 21.259842519685044,
            "unit": "PT"
          },
          "indentEnd": {
            "magnitude": 2.7,
            "unit": "PT"
          },
          "keepLinesTogether": true
        },
        "bullet": {
          "listId": "kix.list.1",
          "textStyle": {
            "fontSize": {
              "magnitude": 10,
              "unit": "PT"
            },
            "weightedFontFamily": {
              "fontFamily": "Raleway",
              "weight": 400
            }
          }
        },
        "runs": [
          {
            "startIndex": 4537,
            "endIndex": 4711,
            "textPreview": "Improved product quality across web and mobile applications by executi",
            "textStyle": {
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          }
        ]
      }
    },
    {
      "startIndex": 4711,
      "endIndex": 4910,
      "paragraph": {
        "label": "Strengthened API and system integration coverage by testing REST services with Postman and",
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "alignment": "JUSTIFIED",
          "lineSpacing": 150,
          "direction": "LEFT_TO_RIGHT",
          "indentFirstLine": {
            "magnitude": 21.259842519685044,
            "unit": "PT"
          },
          "indentEnd": {
            "magnitude": 2.7,
            "unit": "PT"
          },
          "keepLinesTogether": true
        },
        "bullet": {
          "listId": "kix.list.1",
          "textStyle": {
            "fontSize": {
              "magnitude": 10,
              "unit": "PT"
            },
            "weightedFontFamily": {
              "fontFamily": "Raleway",
              "weight": 400
            }
          }
        },
        "runs": [
          {
            "startIndex": 4711,
            "endIndex": 4910,
            "textPreview": "Strengthened API and system integration coverage by testing REST servi",
            "textStyle": {
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          }
        ]
      }
    },
    {
      "startIndex": 4910,
      "endIndex": 5058,
      "paragraph": {
        "label": "Improved test coverage and regression consistency by creating, executing, and maintaining ",
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "alignment": "JUSTIFIED",
          "lineSpacing": 150,
          "direction": "LEFT_TO_RIGHT",
          "indentFirstLine": {
            "magnitude": 21.259842519685044,
            "unit": "PT"
          },
          "indentEnd": {
            "magnitude": 2.7,
            "unit": "PT"
          },
          "keepLinesTogether": true
        },
        "bullet": {
          "listId": "kix.list.1",
          "textStyle": {
            "fontSize": {
              "magnitude": 11,
              "unit": "PT"
            },
            "weightedFontFamily": {
              "fontFamily": "Raleway",
              "weight": 400
            }
          }
        },
        "runs": [
          {
            "startIndex": 4910,
            "endIndex": 5057,
            "textPreview": "Improved test coverage and regression consistency by creating, executi",
            "textStyle": {
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          },
          {
            "startIndex": 5057,
            "endIndex": 5058,
            "textPreview": "\n",
            "textStyle": {
              "fontSize": {
                "magnitude": 12,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          }
        ]
      }
    },
    {
      "startIndex": 5058,
      "endIndex": 5068,
      "paragraph": {
        "label": "Education",
        "paragraphStyle": {
          "headingId": "h.109wuwsl7nok",
          "namedStyleType": "HEADING_2",
          "lineSpacing": 115,
          "direction": "LEFT_TO_RIGHT",
          "spaceAbove": {
            "magnitude": 8,
            "unit": "PT"
          },
          "spaceBelow": {
            "magnitude": 8,
            "unit": "PT"
          },
          "borderBottom": {
            "color": {
              "color": {
                "rgbColor": {}
              }
            },
            "width": {
              "magnitude": 1.5,
              "unit": "PT"
            },
            "padding": {
              "magnitude": 4,
              "unit": "PT"
            },
            "dashStyle": "SOLID"
          },
          "indentEnd": {
            "magnitude": 2.7,
            "unit": "PT"
          },
          "keepWithNext": true
        },
        "runs": [
          {
            "startIndex": 5058,
            "endIndex": 5067,
            "textPreview": "Education",
            "textStyle": {
              "bold": false,
              "foregroundColor": {
                "color": {
                  "rgbColor": {}
                }
              },
              "fontSize": {
                "magnitude": 16,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          },
          {
            "startIndex": 5067,
            "endIndex": 5068,
            "textPreview": "\n",
            "textStyle": {
              "bold": true,
              "fontSize": {
                "magnitude": 12,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          }
        ]
      }
    },
    {
      "startIndex": 5068,
      "endIndex": 5069,
      "sectionBreak": {
        "sectionStyle": {
          "columnProperties": [
            {
              "width": {
                "magnitude": 242.187,
                "unit": "PT"
              },
              "paddingEnd": {
                "magnitude": 36,
                "unit": "PT"
              }
            },
            {
              "width": {
                "magnitude": 242.187,
                "unit": "PT"
              },
              "paddingEnd": {
                "unit": "PT"
              }
            }
          ],
          "columnSeparatorStyle": "NONE",
          "contentDirection": "LEFT_TO_RIGHT",
          "marginTop": {
            "magnitude": 30.95,
            "unit": "PT"
          },
          "marginBottom": {
            "magnitude": 31.972440944881953,
            "unit": "PT"
          },
          "marginRight": {
            "magnitude": 37.45,
            "unit": "PT"
          },
          "marginLeft": {
            "magnitude": 37.45,
            "unit": "PT"
          },
          "marginHeader": {
            "magnitude": 36,
            "unit": "PT"
          },
          "marginFooter": {
            "magnitude": 36,
            "unit": "PT"
          },
          "sectionType": "CONTINUOUS",
          "flipPageOrientation": false
        }
      }
    },
    {
      "startIndex": 5069,
      "endIndex": 5334,
      "paragraph": {
        "label": "Kharkiv National University of Radioelectronics\u000bMSc, Software Engineering — 2020\u000bBSc, Soft",
        "paragraphStyle": {
          "namedStyleType": "NORMAL_TEXT",
          "lineSpacing": 115,
          "direction": "LEFT_TO_RIGHT",
          "spaceBelow": {
            "magnitude": 12,
            "unit": "PT"
          },
          "indentEnd": {
            "magnitude": 2.7,
            "unit": "PT"
          }
        },
        "runs": [
          {
            "startIndex": 5069,
            "endIndex": 5117,
            "textPreview": "Kharkiv National University of Radioelectronics\u000b",
            "textStyle": {
              "bold": true,
              "fontSize": {
                "magnitude": 12,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          },
          {
            "startIndex": 5117,
            "endIndex": 5182,
            "textPreview": "MSc, Software Engineering — 2020\u000bBSc, Software Engineering — 2018",
            "textStyle": {
              "fontSize": {
                "magnitude": 12,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          },
          {
            "startIndex": 5182,
            "endIndex": 5198,
            "textPreview": "\u000b\u000bCertification:",
            "textStyle": {
              "bold": true,
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          },
          {
            "startIndex": 5198,
            "endIndex": 5252,
            "textPreview": " ISTQB Certified Tester Foundation Level (CTFL), 2020\u000b",
            "textStyle": {
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          },
          {
            "startIndex": 5252,
            "endIndex": 5260,
            "textPreview": "Domains:",
            "textStyle": {
              "bold": true,
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          },
          {
            "startIndex": 5260,
            "endIndex": 5290,
            "textPreview": " E-commerce, SaaS, Healthcare\u000b",
            "textStyle": {
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          },
          {
            "startIndex": 5290,
            "endIndex": 5300,
            "textPreview": "Languages:",
            "textStyle": {
              "bold": true,
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          },
          {
            "startIndex": 5300,
            "endIndex": 5333,
            "textPreview": " English (C1), Ukrainian (Native)",
            "textStyle": {
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          },
          {
            "startIndex": 5333,
            "endIndex": 5334,
            "textPreview": "\n",
            "textStyle": {
              "bold": true,
              "fontSize": {
                "magnitude": 11,
                "unit": "PT"
              },
              "weightedFontFamily": {
                "fontFamily": "Raleway",
                "weight": 400
              }
            }
          }
        ]
      }
    }
  ]
}
```
