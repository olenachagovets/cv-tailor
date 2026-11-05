# CV Formatting Style Guide

Source: [Olena_Machula_CV_master](https://docs.google.com/document/d/130PuP8feSfTM03H6zOb8s6N2o5O8MyFvSJ9rkOkpzvg/edit)  
Updated: 5 November 2026  
Authoritative formatting source for this revision: attached `Olena_Machula_CV_master-4.docx`; this supersedes the earlier Google Docs extraction.  
Scope: formatting specification, not a résumé content export.

## How to use this guide

Reproduce the explicitly applied formatting below when creating a Google Docs or Word résumé. Direct text and paragraph formatting takes precedence over stored named-style defaults. Markdown itself cannot enforce fonts, point sizes, page margins, columns, paragraph borders, or pagination; this file records those settings for use in a document editor.

## Page setup and sections

| Setting | Source value |
| --- | --- |
| Mode | Pages |
| Paper | A4 portrait; DOCX stores 11900 × 16840 twips = 595 × 842 pt, approximately 209.90 × 297.04 mm |
| Top and bottom margins, all three sections | **1.0 cm (10 mm)** = 28.346456692913385 pt each |
| Left and right margins, all three sections | **1.3 cm (13 mm)** = 36.85039370078741 pt each |
| Header and footer margins | 36 pt each |
| Text direction | Left to right |
| Column separator | None |
| Section transitions | Continuous |
| Header section | Two columns, each 230.798 pt; first-column gap 59.9775 pt; margins as above |
| Main body section | Single column; no column element in the body section properties; margins as above |
| Education content section | **One full-width column**, 521.574 pt stored width; no column gap; margins as above |

Units: 1 pt = 20 twips; 1 inch = 1440 twips = 25.4 mm. Top/bottom: 566.9291338582677 ÷ 1440 × 25.4 = 10 mm. Left/right: 737.0078740157481 ÷ 1440 × 25.4 = 13 mm. Header/footer offsets are 720 twips = 36 pt = 12.7 mm. Display converted values rounded to two decimals when needed; preserve the stored values in the appendix. Do not reuse the former 72 pt document defaults or the older section margins.

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
| Name | Start / left, inherited | **1.5 (150%)** | 0 / 0 pt, inherited |
| Professional title | Start / left, inherited | **1.5 (150%)** | 0 / 0 pt |
| Contact paragraphs | End / right | **1.5 (150%)** | 0 / 0 pt |
| Summary | Justified | 1.25 (125%) | 0 / 0 pt |
| Section headings | Start / left, inherited | 1.15 (115%) | 8 / 8 pt |
| Skill category paragraphs | Justified | 1.15 (115%) | 6 / 6 pt |
| First job heading | Start / left, inherited | **1.5 (150%)** | 4 / 2 pt |
| Later job headings | Start / left, inherited | **1.5 (150%)** | 7 / 2 pt |
| Experience bullets | Justified | **1.5 (150%)** | 0 / 0 pt, inherited |
| Education details | Start / left, inherited | 1.15 (115%) | 0 / 12 pt |

**Experience job headings, date/location lines and every experience bullet use 1.5 line spacing.** The standalone “Experience” section heading uses 1.15, like the other section headings. Do not apply 1.15 to the experience entries.

Word encodes automatic line spacing in 240ths of a line: 360 ÷ 240 = 1.5; 300 ÷ 240 = 1.25; 276 ÷ 240 = 1.15. These are multiples, not fixed point leading. Before/after paragraph spacing is separate: for example 160 twips ÷ 20 = 8 pt. Experience bullets do not explicitly specify before/after spacing; no paragraph spacing is set by Normal or document defaults in this DOCX.

## Heading rules and dividers

- Skills, Experience, and Education use the semantic HEADING_2 style with direct visual overrides.
- Each section heading has a black solid bottom paragraph border: 1.5 pt wide, with 4 pt padding.
- Section headings have an end indent of 2.7 pt.
- Stored HEADING_2 defaults keep lines together and keep the heading with the next paragraph; Education also explicitly sets keepWithNext.
- The name and professional title are NORMAL_TEXT paragraphs with custom sizes, rather than TITLE or SUBTITLE styles.
- The summary has no separate visible section heading.

## Header structure and indents

- **Email and LinkedIn must remain plain text, with no embedded hyperlinks**, as confirmed by the user. Do not add a `mailto:` target, LinkedIn hyperlink, hyperlink styling, or automatic link conversion. Preserve the visible email address and profile URL.
- Put name and professional title in the first header column; contact details use end/right alignment.
- Phone and email share a paragraph separated by a soft line break.
- LinkedIn and availability share another paragraph separated by a soft line break.
- Name end indent: approximately 0.05 pt.
- Professional-title end indent: −10.825 pt.
- Contact paragraph end indent: 2.7 pt.
- LinkedIn/availability paragraph left indent: 21.259842519685023 pt; relative first-line indent: 0 pt. Do not add another 21.26 pt to its first line.

## Experience structure and bullets

- A job heading combines the role/company line and date/location line in one paragraph, separated by a soft line break.
- Keep each job heading with the following paragraph.
- Use a solid round bullet: ● (Unicode U+25CF), Word numbering ID 1, level 0.
- List definition: bullet alignment START; first-line indent 21.259842519685044 pt; text start indent 0 pt.
- Each actual bullet paragraph also explicitly sets first-line indent 21.259842519685044 pt and end indent 2.7 pt.
- Preserve these unusual source indent values for literal reproduction; do not silently replace them with conventional hanging indents.
- Keep each bullet paragraph's lines together.
- Bullet glyph font in the list definition: Noto Sans Symbols, weight 400. Per-paragraph bullet text styles specify Raleway.
- Most bullet markers are 11 pt; the first two NearShorePartner.ch bullet markers are 10 pt, although their text remains 11 pt.
- Experience bullets in the source have no terminal full stops.

## Education and additional details

- Education is followed by a continuous **single-column, full-width section**. Do not use the former two-column education layout.
- The education content is one paragraph using soft line breaks between the university, degree lines, certification, domains and languages.
- There is **one soft line break** after the BSc line and before “Certification:”. There are **no empty lines** between the degree list and certification.
- Education uses **1.15 line spacing**, 12 pt space after the entire paragraph, and a 2.7 pt right indent.
- The Education heading stays in the full-width body section. The continuous section after it also has one column. University, degrees, certification, domains and languages follow vertically across the available page width; there is no side-by-side block.
- Sequence: university → MSc → BSc → Certification → Domains → Languages, with one soft line break between consecutive entries. Line breaks within wrapped text are automatic and depend on available full-page text width.
- University: 12 pt bold; degree lines: 12 pt regular. Certification, Domains and Languages: 11 pt, bold labels and regular values. Education heading: 16 pt regular.
- Keep the institution bold and degree values regular.
- Keep inline labels bold and their values regular.

## Source inconsistencies and reproduction limits

These are observed details, not suggested changes:

- Education is 16 pt while the other visible section headings are 15 pt.
- The first letter “Q” in the NearShorePartner.ch job title is 12 pt; the remaining title text is 13 pt.
- Two NearShorePartner.ch bullet markers are 10 pt rather than the usual 11 pt.
- The final NearShorePartner.ch bullet has an 11 pt paragraph mark in this DOCX; the older guide’s 12 pt newline value is superseded.
- The name's paragraph-ending newline is 11 pt rather than 20 pt.
- The Education heading ends with a bold 12 pt newline, although the visible heading is regular 16 pt.
- The first contact paragraph has an underlined paragraph-ending newline; its visible contact text does not explicitly set underline or a hyperlink.
- Tiny and negative end indents are preserved in the source.
- Visible text explicitly uses Raleway. The DOCX Normal style has no font settings; document default size is 10.5 pt. The stored Heading2 style is Calibri, 13 pt, bold, blue (#4F81BD), overridden by the directly formatted visible headings.
- No tables appear in the source body. Section column layouts are used rather than layout tables.
- The previous master-3 DOCX rendered to three pages locally; that pagination does not establish the page count of this revised master-4 file. The current education section is full-width and has no blank lines before certification. Page count must be checked in the final editor; do not reduce experience line spacing or alter margins to force a page count.
- No additional colours, icons, backgrounds or graphics should be inferred from this specification.

## Complete current formatting metadata

This appendix replaces the old Google Docs API snapshot. It preserves the current DOCX section, style, numbering, paragraph and run settings, including unused styles. Only short text previews are retained. Paragraph-mark properties are separate from visible run properties. Missing direct properties require style inheritance; do not treat a paragraph mark as formatting for all visible text.

```json
{
  "sourceFilename": "Olena_Machula_CV_master-4.docx",
  "sourceSHA256": "3e7d8f9b795769d4e738975c4f7e780a0d2a1cd35a4b04abe0b2b71e7e4f24af",
  "units": {
    "pageAndIndent": "twips (20 per pt)",
    "fontSize": "half-points",
    "automaticLineSpacing": "240ths of a line",
    "borderSize": "eighth-points"
  },
  "sections": [
    {
      "tag": "sectPr",
      "attributes": {},
      "children": [
        {
          "tag": "pgSz",
          "attributes": {
            "h": "16840",
            "w": "11900",
            "orient": "portrait"
          },
          "children": []
        },
        {
          "tag": "pgMar",
          "attributes": {
            "bottom": "566.9291338582677",
            "top": "566.9291338582677",
            "left": "737.0078740157481",
            "right": "737.0078740157481",
            "header": "720",
            "footer": "720"
          },
          "children": []
        },
        {
          "tag": "pgNumType",
          "attributes": {
            "start": "1"
          },
          "children": []
        },
        {
          "tag": "cols",
          "attributes": {
            "equalWidth": "0",
            "num": "2"
          },
          "children": [
            {
              "tag": "col",
              "attributes": {
                "space": "1199.55",
                "w": "4615.96"
              },
              "children": []
            },
            {
              "tag": "col",
              "attributes": {
                "space": "0",
                "w": "4615.96"
              },
              "children": []
            }
          ]
        }
      ]
    },
    {
      "tag": "sectPr",
      "attributes": {},
      "children": [
        {
          "tag": "type",
          "attributes": {
            "val": "continuous"
          },
          "children": []
        },
        {
          "tag": "pgSz",
          "attributes": {
            "h": "16840",
            "w": "11900",
            "orient": "portrait"
          },
          "children": []
        },
        {
          "tag": "pgMar",
          "attributes": {
            "bottom": "566.9291338582677",
            "top": "566.9291338582677",
            "left": "737.0078740157481",
            "right": "737.0078740157481",
            "header": "720",
            "footer": "720"
          },
          "children": []
        }
      ]
    },
    {
      "tag": "sectPr",
      "attributes": {},
      "children": [
        {
          "tag": "type",
          "attributes": {
            "val": "continuous"
          },
          "children": []
        },
        {
          "tag": "pgSz",
          "attributes": {
            "h": "16840",
            "w": "11900",
            "orient": "portrait"
          },
          "children": []
        },
        {
          "tag": "pgMar",
          "attributes": {
            "bottom": "566.9291338582677",
            "top": "566.9291338582677",
            "left": "737.0078740157481",
            "right": "737.0078740157481",
            "header": "720",
            "footer": "720"
          },
          "children": []
        },
        {
          "tag": "cols",
          "attributes": {
            "equalWidth": "0",
            "num": "1"
          },
          "children": [
            {
              "tag": "col",
              "attributes": {
                "space": "0",
                "w": "10431.48"
              },
              "children": []
            }
          ]
        }
      ]
    }
  ],
  "styles": {
    "tag": "styles",
    "attributes": {},
    "children": [
      {
        "tag": "docDefaults",
        "attributes": {},
        "children": [
          {
            "tag": "rPrDefault",
            "attributes": {},
            "children": [
              {
                "tag": "rPr",
                "attributes": {},
                "children": [
                  {
                    "tag": "sz",
                    "attributes": {
                      "val": "21"
                    },
                    "children": []
                  },
                  {
                    "tag": "szCs",
                    "attributes": {
                      "val": "21"
                    },
                    "children": []
                  },
                  {
                    "tag": "lang",
                    "attributes": {
                      "val": "en"
                    },
                    "children": []
                  }
                ]
              }
            ]
          },
          {
            "tag": "pPrDefault",
            "attributes": {},
            "children": [
              {
                "tag": "pPr",
                "attributes": {},
                "children": []
              }
            ]
          }
        ]
      },
      {
        "tag": "style",
        "attributes": {
          "type": "table",
          "styleId": "TableNormal",
          "default": "1"
        },
        "children": [
          {
            "tag": "name",
            "attributes": {
              "val": "TableNormal"
            },
            "children": []
          },
          {
            "tag": "tblPr",
            "attributes": {},
            "children": [
              {
                "tag": "tblCellMar",
                "attributes": {},
                "children": [
                  {
                    "tag": "top",
                    "attributes": {
                      "w": "100.0",
                      "type": "dxa"
                    },
                    "children": []
                  },
                  {
                    "tag": "left",
                    "attributes": {
                      "w": "100.0",
                      "type": "dxa"
                    },
                    "children": []
                  },
                  {
                    "tag": "bottom",
                    "attributes": {
                      "w": "100.0",
                      "type": "dxa"
                    },
                    "children": []
                  },
                  {
                    "tag": "right",
                    "attributes": {
                      "w": "100.0",
                      "type": "dxa"
                    },
                    "children": []
                  }
                ]
              }
            ]
          }
        ]
      },
      {
        "tag": "style",
        "attributes": {
          "type": "paragraph",
          "styleId": "Normal",
          "default": "1"
        },
        "children": [
          {
            "tag": "name",
            "attributes": {
              "val": "normal"
            },
            "children": []
          }
        ]
      },
      {
        "tag": "style",
        "attributes": {
          "type": "paragraph",
          "styleId": "Heading1"
        },
        "children": [
          {
            "tag": "name",
            "attributes": {
              "val": "heading 1"
            },
            "children": []
          },
          {
            "tag": "basedOn",
            "attributes": {
              "val": "Normal"
            },
            "children": []
          },
          {
            "tag": "next",
            "attributes": {
              "val": "Normal"
            },
            "children": []
          },
          {
            "tag": "pPr",
            "attributes": {},
            "children": [
              {
                "tag": "keepNext",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "keepLines",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "spacing",
                "attributes": {
                  "before": "480",
                  "lineRule": "auto"
                },
                "children": []
              }
            ]
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Calibri",
                  "cs": "Calibri",
                  "eastAsia": "Calibri",
                  "hAnsi": "Calibri"
                },
                "children": []
              },
              {
                "tag": "b",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "bCs",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "color",
                "attributes": {
                  "val": "366091"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "28"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "28"
                },
                "children": []
              }
            ]
          }
        ]
      },
      {
        "tag": "style",
        "attributes": {
          "type": "paragraph",
          "styleId": "Heading2"
        },
        "children": [
          {
            "tag": "name",
            "attributes": {
              "val": "heading 2"
            },
            "children": []
          },
          {
            "tag": "basedOn",
            "attributes": {
              "val": "Normal"
            },
            "children": []
          },
          {
            "tag": "next",
            "attributes": {
              "val": "Normal"
            },
            "children": []
          },
          {
            "tag": "pPr",
            "attributes": {},
            "children": [
              {
                "tag": "keepNext",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "keepLines",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "spacing",
                "attributes": {
                  "before": "200",
                  "lineRule": "auto"
                },
                "children": []
              }
            ]
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Calibri",
                  "cs": "Calibri",
                  "eastAsia": "Calibri",
                  "hAnsi": "Calibri"
                },
                "children": []
              },
              {
                "tag": "b",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "bCs",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "color",
                "attributes": {
                  "val": "4f81bd"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "26"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "26"
                },
                "children": []
              }
            ]
          }
        ]
      },
      {
        "tag": "style",
        "attributes": {
          "type": "paragraph",
          "styleId": "Heading3"
        },
        "children": [
          {
            "tag": "name",
            "attributes": {
              "val": "heading 3"
            },
            "children": []
          },
          {
            "tag": "basedOn",
            "attributes": {
              "val": "Normal"
            },
            "children": []
          },
          {
            "tag": "next",
            "attributes": {
              "val": "Normal"
            },
            "children": []
          },
          {
            "tag": "pPr",
            "attributes": {},
            "children": [
              {
                "tag": "keepNext",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "keepLines",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "spacing",
                "attributes": {
                  "before": "200",
                  "lineRule": "auto"
                },
                "children": []
              }
            ]
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Calibri",
                  "cs": "Calibri",
                  "eastAsia": "Calibri",
                  "hAnsi": "Calibri"
                },
                "children": []
              },
              {
                "tag": "b",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "bCs",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "color",
                "attributes": {
                  "val": "4f81bd"
                },
                "children": []
              }
            ]
          }
        ]
      },
      {
        "tag": "style",
        "attributes": {
          "type": "paragraph",
          "styleId": "Heading4"
        },
        "children": [
          {
            "tag": "name",
            "attributes": {
              "val": "heading 4"
            },
            "children": []
          },
          {
            "tag": "basedOn",
            "attributes": {
              "val": "Normal"
            },
            "children": []
          },
          {
            "tag": "next",
            "attributes": {
              "val": "Normal"
            },
            "children": []
          },
          {
            "tag": "pPr",
            "attributes": {},
            "children": [
              {
                "tag": "keepNext",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "keepLines",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "spacing",
                "attributes": {
                  "before": "200",
                  "lineRule": "auto"
                },
                "children": []
              }
            ]
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Calibri",
                  "cs": "Calibri",
                  "eastAsia": "Calibri",
                  "hAnsi": "Calibri"
                },
                "children": []
              },
              {
                "tag": "b",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "bCs",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "i",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "iCs",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "color",
                "attributes": {
                  "val": "4f81bd"
                },
                "children": []
              }
            ]
          }
        ]
      },
      {
        "tag": "style",
        "attributes": {
          "type": "paragraph",
          "styleId": "Heading5"
        },
        "children": [
          {
            "tag": "name",
            "attributes": {
              "val": "heading 5"
            },
            "children": []
          },
          {
            "tag": "basedOn",
            "attributes": {
              "val": "Normal"
            },
            "children": []
          },
          {
            "tag": "next",
            "attributes": {
              "val": "Normal"
            },
            "children": []
          },
          {
            "tag": "pPr",
            "attributes": {},
            "children": [
              {
                "tag": "keepNext",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "keepLines",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "spacing",
                "attributes": {
                  "before": "200",
                  "lineRule": "auto"
                },
                "children": []
              }
            ]
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Calibri",
                  "cs": "Calibri",
                  "eastAsia": "Calibri",
                  "hAnsi": "Calibri"
                },
                "children": []
              },
              {
                "tag": "color",
                "attributes": {
                  "val": "243f61"
                },
                "children": []
              }
            ]
          }
        ]
      },
      {
        "tag": "style",
        "attributes": {
          "type": "paragraph",
          "styleId": "Heading6"
        },
        "children": [
          {
            "tag": "name",
            "attributes": {
              "val": "heading 6"
            },
            "children": []
          },
          {
            "tag": "basedOn",
            "attributes": {
              "val": "Normal"
            },
            "children": []
          },
          {
            "tag": "next",
            "attributes": {
              "val": "Normal"
            },
            "children": []
          },
          {
            "tag": "pPr",
            "attributes": {},
            "children": [
              {
                "tag": "keepNext",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "keepLines",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "spacing",
                "attributes": {
                  "before": "200",
                  "lineRule": "auto"
                },
                "children": []
              }
            ]
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Calibri",
                  "cs": "Calibri",
                  "eastAsia": "Calibri",
                  "hAnsi": "Calibri"
                },
                "children": []
              },
              {
                "tag": "i",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "iCs",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "color",
                "attributes": {
                  "val": "243f61"
                },
                "children": []
              }
            ]
          }
        ]
      },
      {
        "tag": "style",
        "attributes": {
          "type": "paragraph",
          "styleId": "Title"
        },
        "children": [
          {
            "tag": "name",
            "attributes": {
              "val": "Title"
            },
            "children": []
          },
          {
            "tag": "basedOn",
            "attributes": {
              "val": "Normal"
            },
            "children": []
          },
          {
            "tag": "next",
            "attributes": {
              "val": "Normal"
            },
            "children": []
          },
          {
            "tag": "pPr",
            "attributes": {},
            "children": [
              {
                "tag": "pBdr",
                "attributes": {},
                "children": [
                  {
                    "tag": "bottom",
                    "attributes": {
                      "color": "4f81bd",
                      "space": "4",
                      "sz": "8",
                      "val": "single"
                    },
                    "children": []
                  }
                ]
              },
              {
                "tag": "spacing",
                "attributes": {
                  "after": "300",
                  "lineRule": "auto"
                },
                "children": []
              }
            ]
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Calibri",
                  "cs": "Calibri",
                  "eastAsia": "Calibri",
                  "hAnsi": "Calibri"
                },
                "children": []
              },
              {
                "tag": "color",
                "attributes": {
                  "val": "17365d"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "52"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "52"
                },
                "children": []
              }
            ]
          }
        ]
      },
      {
        "tag": "style",
        "attributes": {
          "type": "paragraph",
          "styleId": "Subtitle"
        },
        "children": [
          {
            "tag": "name",
            "attributes": {
              "val": "Subtitle"
            },
            "children": []
          },
          {
            "tag": "basedOn",
            "attributes": {
              "val": "Normal"
            },
            "children": []
          },
          {
            "tag": "next",
            "attributes": {
              "val": "Normal"
            },
            "children": []
          },
          {
            "tag": "pPr",
            "attributes": {},
            "children": []
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Calibri",
                  "cs": "Calibri",
                  "eastAsia": "Calibri",
                  "hAnsi": "Calibri"
                },
                "children": []
              },
              {
                "tag": "i",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "iCs",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "color",
                "attributes": {
                  "val": "4f81bd"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "24"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "24"
                },
                "children": []
              }
            ]
          }
        ]
      },
      {
        "tag": "style",
        "attributes": {
          "type": "paragraph",
          "styleId": "TableofFigures"
        },
        "children": [
          {
            "tag": "name",
            "attributes": {
              "val": "table of figures"
            },
            "children": []
          },
          {
            "tag": "basedOn",
            "attributes": {
              "val": "Normal"
            },
            "children": []
          },
          {
            "tag": "next",
            "attributes": {
              "val": "Normal"
            },
            "children": []
          }
        ]
      }
    ]
  },
  "numbering": {
    "tag": "numbering",
    "attributes": {},
    "children": [
      {
        "tag": "abstractNum",
        "attributes": {
          "abstractNumId": "1"
        },
        "children": [
          {
            "tag": "lvl",
            "attributes": {
              "ilvl": "0"
            },
            "children": [
              {
                "tag": "start",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "numFmt",
                "attributes": {
                  "val": "bullet"
                },
                "children": []
              },
              {
                "tag": "lvlText",
                "attributes": {
                  "val": "●"
                },
                "children": []
              },
              {
                "tag": "lvlJc",
                "attributes": {
                  "val": "left"
                },
                "children": []
              },
              {
                "tag": "pPr",
                "attributes": {},
                "children": [
                  {
                    "tag": "ind",
                    "attributes": {
                      "left": "0",
                      "firstLine": "425.19685039370086"
                    },
                    "children": []
                  }
                ]
              },
              {
                "tag": "rPr",
                "attributes": {},
                "children": [
                  {
                    "tag": "rFonts",
                    "attributes": {
                      "ascii": "Noto Sans Symbols",
                      "cs": "Noto Sans Symbols",
                      "eastAsia": "Noto Sans Symbols",
                      "hAnsi": "Noto Sans Symbols"
                    },
                    "children": []
                  }
                ]
              }
            ]
          },
          {
            "tag": "lvl",
            "attributes": {
              "ilvl": "1"
            },
            "children": [
              {
                "tag": "start",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "numFmt",
                "attributes": {
                  "val": "bullet"
                },
                "children": []
              },
              {
                "tag": "lvlText",
                "attributes": {
                  "val": ""
                },
                "children": []
              },
              {
                "tag": "lvlJc",
                "attributes": {
                  "val": "left"
                },
                "children": []
              },
              {
                "tag": "pPr",
                "attributes": {},
                "children": [
                  {
                    "tag": "ind",
                    "attributes": {
                      "left": "0",
                      "firstLine": "0"
                    },
                    "children": []
                  }
                ]
              },
              {
                "tag": "rPr",
                "attributes": {},
                "children": []
              }
            ]
          },
          {
            "tag": "lvl",
            "attributes": {
              "ilvl": "2"
            },
            "children": [
              {
                "tag": "start",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "numFmt",
                "attributes": {
                  "val": "bullet"
                },
                "children": []
              },
              {
                "tag": "lvlText",
                "attributes": {
                  "val": ""
                },
                "children": []
              },
              {
                "tag": "lvlJc",
                "attributes": {
                  "val": "left"
                },
                "children": []
              },
              {
                "tag": "pPr",
                "attributes": {},
                "children": [
                  {
                    "tag": "ind",
                    "attributes": {
                      "left": "0",
                      "firstLine": "0"
                    },
                    "children": []
                  }
                ]
              },
              {
                "tag": "rPr",
                "attributes": {},
                "children": []
              }
            ]
          },
          {
            "tag": "lvl",
            "attributes": {
              "ilvl": "3"
            },
            "children": [
              {
                "tag": "start",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "numFmt",
                "attributes": {
                  "val": "bullet"
                },
                "children": []
              },
              {
                "tag": "lvlText",
                "attributes": {
                  "val": ""
                },
                "children": []
              },
              {
                "tag": "lvlJc",
                "attributes": {
                  "val": "left"
                },
                "children": []
              },
              {
                "tag": "pPr",
                "attributes": {},
                "children": [
                  {
                    "tag": "ind",
                    "attributes": {
                      "left": "0",
                      "firstLine": "0"
                    },
                    "children": []
                  }
                ]
              },
              {
                "tag": "rPr",
                "attributes": {},
                "children": []
              }
            ]
          },
          {
            "tag": "lvl",
            "attributes": {
              "ilvl": "4"
            },
            "children": [
              {
                "tag": "start",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "numFmt",
                "attributes": {
                  "val": "bullet"
                },
                "children": []
              },
              {
                "tag": "lvlText",
                "attributes": {
                  "val": ""
                },
                "children": []
              },
              {
                "tag": "lvlJc",
                "attributes": {
                  "val": "left"
                },
                "children": []
              },
              {
                "tag": "pPr",
                "attributes": {},
                "children": [
                  {
                    "tag": "ind",
                    "attributes": {
                      "left": "0",
                      "firstLine": "0"
                    },
                    "children": []
                  }
                ]
              },
              {
                "tag": "rPr",
                "attributes": {},
                "children": []
              }
            ]
          },
          {
            "tag": "lvl",
            "attributes": {
              "ilvl": "5"
            },
            "children": [
              {
                "tag": "start",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "numFmt",
                "attributes": {
                  "val": "bullet"
                },
                "children": []
              },
              {
                "tag": "lvlText",
                "attributes": {
                  "val": ""
                },
                "children": []
              },
              {
                "tag": "lvlJc",
                "attributes": {
                  "val": "left"
                },
                "children": []
              },
              {
                "tag": "pPr",
                "attributes": {},
                "children": [
                  {
                    "tag": "ind",
                    "attributes": {
                      "left": "0",
                      "firstLine": "0"
                    },
                    "children": []
                  }
                ]
              },
              {
                "tag": "rPr",
                "attributes": {},
                "children": []
              }
            ]
          },
          {
            "tag": "lvl",
            "attributes": {
              "ilvl": "6"
            },
            "children": [
              {
                "tag": "start",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "numFmt",
                "attributes": {
                  "val": "bullet"
                },
                "children": []
              },
              {
                "tag": "lvlText",
                "attributes": {
                  "val": ""
                },
                "children": []
              },
              {
                "tag": "lvlJc",
                "attributes": {
                  "val": "left"
                },
                "children": []
              },
              {
                "tag": "pPr",
                "attributes": {},
                "children": [
                  {
                    "tag": "ind",
                    "attributes": {
                      "left": "0",
                      "firstLine": "0"
                    },
                    "children": []
                  }
                ]
              },
              {
                "tag": "rPr",
                "attributes": {},
                "children": []
              }
            ]
          },
          {
            "tag": "lvl",
            "attributes": {
              "ilvl": "7"
            },
            "children": [
              {
                "tag": "start",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "numFmt",
                "attributes": {
                  "val": "bullet"
                },
                "children": []
              },
              {
                "tag": "lvlText",
                "attributes": {
                  "val": ""
                },
                "children": []
              },
              {
                "tag": "lvlJc",
                "attributes": {
                  "val": "left"
                },
                "children": []
              },
              {
                "tag": "pPr",
                "attributes": {},
                "children": [
                  {
                    "tag": "ind",
                    "attributes": {
                      "left": "0",
                      "firstLine": "0"
                    },
                    "children": []
                  }
                ]
              },
              {
                "tag": "rPr",
                "attributes": {},
                "children": []
              }
            ]
          },
          {
            "tag": "lvl",
            "attributes": {
              "ilvl": "8"
            },
            "children": [
              {
                "tag": "start",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "numFmt",
                "attributes": {
                  "val": "bullet"
                },
                "children": []
              },
              {
                "tag": "lvlText",
                "attributes": {
                  "val": ""
                },
                "children": []
              },
              {
                "tag": "lvlJc",
                "attributes": {
                  "val": "left"
                },
                "children": []
              },
              {
                "tag": "pPr",
                "attributes": {},
                "children": [
                  {
                    "tag": "ind",
                    "attributes": {
                      "left": "0",
                      "firstLine": "0"
                    },
                    "children": []
                  }
                ]
              },
              {
                "tag": "rPr",
                "attributes": {},
                "children": []
              }
            ]
          }
        ]
      },
      {
        "tag": "num",
        "attributes": {
          "numId": "1"
        },
        "children": [
          {
            "tag": "abstractNumId",
            "attributes": {
              "val": "1"
            },
            "children": []
          }
        ]
      }
    ]
  },
  "paragraphs": [
    {
      "paragraphIndex": 0,
      "label": "Olena Machula",
      "paragraphProperties": {
        "tag": "pPr",
        "attributes": {},
        "children": [
          {
            "tag": "spacing",
            "attributes": {
              "line": "360",
              "lineRule": "auto"
            },
            "children": []
          },
          {
            "tag": "ind",
            "attributes": {
              "right": "0.9999999999999432"
            },
            "children": []
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              }
            ]
          }
        ]
      },
      "runs": [
        {
          "textPreview": "Olena Machula",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "40"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "40"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        },
        {
          "textPreview": "",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        }
      ]
    },
    {
      "paragraphIndex": 1,
      "label": "Lead QA | Senior Quality Assurance Engineer",
      "paragraphProperties": {
        "tag": "pPr",
        "attributes": {},
        "children": [
          {
            "tag": "spacing",
            "attributes": {
              "after": "0",
              "before": "0",
              "line": "360",
              "lineRule": "auto"
            },
            "children": []
          },
          {
            "tag": "ind",
            "attributes": {
              "right": "-216.50000000000006"
            },
            "children": []
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "36"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "36"
                },
                "children": []
              }
            ]
          }
        ]
      },
      "runs": [
        {
          "textPreview": "Lead QA | Senior Quality Assurance Engineer",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "36"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "36"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        }
      ]
    },
    {
      "paragraphIndex": 2,
      "label": "+380 99 139 73 67chagovets.xx@gmail.com",
      "paragraphProperties": {
        "tag": "pPr",
        "attributes": {},
        "children": [
          {
            "tag": "spacing",
            "attributes": {
              "after": "0",
              "before": "0",
              "line": "360",
              "lineRule": "auto"
            },
            "children": []
          },
          {
            "tag": "ind",
            "attributes": {
              "right": "54"
            },
            "children": []
          },
          {
            "tag": "jc",
            "attributes": {
              "val": "right"
            },
            "children": []
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "u",
                "attributes": {
                  "val": "single"
                },
                "children": []
              }
            ]
          }
        ]
      },
      "runs": [
        {
          "textPreview": "+380 99 139 73 67chagovets.xx@gmail.com",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": [
            {
              "tag": "br",
              "attributes": {
                "type": "textWrapping"
              },
              "children": []
            }
          ]
        },
        {
          "textPreview": "",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        }
      ]
    },
    {
      "paragraphIndex": 3,
      "label": "linkedin.com/in/olena-machulaRemote | Open to EU / UK opportunities ",
      "paragraphProperties": {
        "tag": "pPr",
        "attributes": {},
        "children": [
          {
            "tag": "spacing",
            "attributes": {
              "after": "0",
              "before": "0",
              "line": "360",
              "lineRule": "auto"
            },
            "children": []
          },
          {
            "tag": "ind",
            "attributes": {
              "left": "425.19685039370046",
              "right": "54",
              "firstLine": "0"
            },
            "children": []
          },
          {
            "tag": "jc",
            "attributes": {
              "val": "right"
            },
            "children": []
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              }
            ]
          },
          {
            "tag": "sectPr",
            "attributes": {},
            "children": [
              {
                "tag": "pgSz",
                "attributes": {
                  "h": "16840",
                  "w": "11900",
                  "orient": "portrait"
                },
                "children": []
              },
              {
                "tag": "pgMar",
                "attributes": {
                  "bottom": "566.9291338582677",
                  "top": "566.9291338582677",
                  "left": "737.0078740157481",
                  "right": "737.0078740157481",
                  "header": "720",
                  "footer": "720"
                },
                "children": []
              },
              {
                "tag": "pgNumType",
                "attributes": {
                  "start": "1"
                },
                "children": []
              },
              {
                "tag": "cols",
                "attributes": {
                  "equalWidth": "0",
                  "num": "2"
                },
                "children": [
                  {
                    "tag": "col",
                    "attributes": {
                      "space": "1199.55",
                      "w": "4615.96"
                    },
                    "children": []
                  },
                  {
                    "tag": "col",
                    "attributes": {
                      "space": "0",
                      "w": "4615.96"
                    },
                    "children": []
                  }
                ]
              }
            ]
          }
        ]
      },
      "runs": [
        {
          "textPreview": "linkedin.com/in/olena-machulaRemote | Open to EU / UK opportunities ",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": [
            {
              "tag": "br",
              "attributes": {
                "type": "textWrapping"
              },
              "children": []
            }
          ]
        }
      ]
    },
    {
      "paragraphIndex": 4,
      "label": "QA Lead with 7+ years of software quality assurance experience and 3 years leading a team ",
      "paragraphProperties": {
        "tag": "pPr",
        "attributes": {},
        "children": [
          {
            "tag": "spacing",
            "attributes": {
              "after": "0",
              "before": "0",
              "line": "300",
              "lineRule": "auto"
            },
            "children": []
          },
          {
            "tag": "jc",
            "attributes": {
              "val": "both"
            },
            "children": []
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              }
            ]
          }
        ]
      },
      "runs": [
        {
          "textPreview": "QA Lead with 7+ years of software quality assurance experience and 3 y",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        },
        {
          "textPreview": "",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        }
      ]
    },
    {
      "paragraphIndex": 5,
      "label": "Skills",
      "paragraphProperties": {
        "tag": "pPr",
        "attributes": {},
        "children": [
          {
            "tag": "pStyle",
            "attributes": {
              "val": "Heading2"
            },
            "children": []
          },
          {
            "tag": "pBdr",
            "attributes": {},
            "children": [
              {
                "tag": "bottom",
                "attributes": {
                  "color": "000000",
                  "space": "4",
                  "sz": "12",
                  "val": "single"
                },
                "children": []
              }
            ]
          },
          {
            "tag": "spacing",
            "attributes": {
              "after": "160",
              "before": "160",
              "line": "276",
              "lineRule": "auto"
            },
            "children": []
          },
          {
            "tag": "ind",
            "attributes": {
              "right": "54"
            },
            "children": []
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "b",
                "attributes": {
                  "val": "0"
                },
                "children": []
              },
              {
                "tag": "bCs",
                "attributes": {
                  "val": "0"
                },
                "children": []
              },
              {
                "tag": "color",
                "attributes": {
                  "val": "000000"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "30"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "30"
                },
                "children": []
              }
            ]
          }
        ]
      },
      "runs": [
        {
          "textPreview": "Skills",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "b",
                "attributes": {
                  "val": "0"
                },
                "children": []
              },
              {
                "tag": "bCs",
                "attributes": {
                  "val": "0"
                },
                "children": []
              },
              {
                "tag": "color",
                "attributes": {
                  "val": "000000"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "30"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "30"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        }
      ]
    },
    {
      "paragraphIndex": 6,
      "label": "QA Leadership & Strategy: QA Leadership, QA Strategy, Test Strategy, Quality Management, T",
      "paragraphProperties": {
        "tag": "pPr",
        "attributes": {},
        "children": [
          {
            "tag": "spacing",
            "attributes": {
              "after": "120",
              "before": "120",
              "line": "276",
              "lineRule": "auto"
            },
            "children": []
          },
          {
            "tag": "jc",
            "attributes": {
              "val": "both"
            },
            "children": []
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              }
            ]
          }
        ]
      },
      "runs": [
        {
          "textPreview": "QA Leadership & Strategy:",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "b",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "bCs",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        },
        {
          "textPreview": " QA Leadership, QA Strategy, Test Strategy, Quality Management, Test P",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        }
      ]
    },
    {
      "paragraphIndex": 7,
      "label": "Release & Quality Ownership: Release Management, Release Validation, Release Readiness, Qu",
      "paragraphProperties": {
        "tag": "pPr",
        "attributes": {},
        "children": [
          {
            "tag": "spacing",
            "attributes": {
              "after": "120",
              "before": "120",
              "line": "276",
              "lineRule": "auto"
            },
            "children": []
          },
          {
            "tag": "jc",
            "attributes": {
              "val": "both"
            },
            "children": []
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              }
            ]
          }
        ]
      },
      "runs": [
        {
          "textPreview": "Release & Quality Ownership:",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "b",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "bCs",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        },
        {
          "textPreview": " Release Management, Release Validation, Release Readiness, Quality Ga",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        }
      ]
    },
    {
      "paragraphIndex": 8,
      "label": "Test Management & Analysis: Requirements Analysis, Test Design, Test Coverage Analysis, Te",
      "paragraphProperties": {
        "tag": "pPr",
        "attributes": {},
        "children": [
          {
            "tag": "spacing",
            "attributes": {
              "after": "120",
              "before": "120",
              "line": "276",
              "lineRule": "auto"
            },
            "children": []
          },
          {
            "tag": "jc",
            "attributes": {
              "val": "both"
            },
            "children": []
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              }
            ]
          }
        ]
      },
      "runs": [
        {
          "textPreview": "Test Management & Analysis:",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "b",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "bCs",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        },
        {
          "textPreview": " Requirements Analysis, Test Design, Test Coverage Analysis, Test Case",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        }
      ]
    },
    {
      "paragraphIndex": 9,
      "label": "API & Backend: REST API Testing, API Integration Testing, HTTP/HTTPS, Postman, Swagger/Ope",
      "paragraphProperties": {
        "tag": "pPr",
        "attributes": {},
        "children": [
          {
            "tag": "spacing",
            "attributes": {
              "after": "120",
              "before": "120",
              "line": "276",
              "lineRule": "auto"
            },
            "children": []
          },
          {
            "tag": "jc",
            "attributes": {
              "val": "both"
            },
            "children": []
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              }
            ]
          }
        ]
      },
      "runs": [
        {
          "textPreview": "API & Backend:",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "b",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "bCs",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        },
        {
          "textPreview": " REST API Testing, API Integration Testing, HTTP/HTTPS, Postman, Swagg",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        }
      ]
    },
    {
      "paragraphIndex": 10,
      "label": "Automation & Quality Engineering: Quality Engineering, Test Automation Strategy, Automatio",
      "paragraphProperties": {
        "tag": "pPr",
        "attributes": {},
        "children": [
          {
            "tag": "spacing",
            "attributes": {
              "after": "120",
              "before": "120",
              "line": "276",
              "lineRule": "auto"
            },
            "children": []
          },
          {
            "tag": "jc",
            "attributes": {
              "val": "both"
            },
            "children": []
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              }
            ]
          }
        ]
      },
      "runs": [
        {
          "textPreview": "Automation & Quality Engineering:",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "b",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "bCs",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        },
        {
          "textPreview": " Quality Engineering, Test Automation Strategy, Automation Coverage Pl",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        }
      ]
    },
    {
      "paragraphIndex": 11,
      "label": "Leadership & Collaboration: QA Team Leadership, Mentoring, Cross-functional Collaboration,",
      "paragraphProperties": {
        "tag": "pPr",
        "attributes": {},
        "children": [
          {
            "tag": "spacing",
            "attributes": {
              "after": "120",
              "before": "120",
              "line": "276",
              "lineRule": "auto"
            },
            "children": []
          },
          {
            "tag": "jc",
            "attributes": {
              "val": "both"
            },
            "children": []
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              }
            ]
          }
        ]
      },
      "runs": [
        {
          "textPreview": "Leadership & Collaboration:",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "b",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "bCs",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        },
        {
          "textPreview": " QA Team Leadership, Mentoring, Cross-functional Collaboration, Stakeh",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        }
      ]
    },
    {
      "paragraphIndex": 12,
      "label": "Experience",
      "paragraphProperties": {
        "tag": "pPr",
        "attributes": {},
        "children": [
          {
            "tag": "pStyle",
            "attributes": {
              "val": "Heading2"
            },
            "children": []
          },
          {
            "tag": "pBdr",
            "attributes": {},
            "children": [
              {
                "tag": "bottom",
                "attributes": {
                  "color": "000000",
                  "space": "4",
                  "sz": "12",
                  "val": "single"
                },
                "children": []
              }
            ]
          },
          {
            "tag": "spacing",
            "attributes": {
              "after": "160",
              "before": "160",
              "line": "276",
              "lineRule": "auto"
            },
            "children": []
          },
          {
            "tag": "ind",
            "attributes": {
              "right": "54"
            },
            "children": []
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "b",
                "attributes": {
                  "val": "0"
                },
                "children": []
              },
              {
                "tag": "bCs",
                "attributes": {
                  "val": "0"
                },
                "children": []
              },
              {
                "tag": "color",
                "attributes": {
                  "val": "000000"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "30"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "30"
                },
                "children": []
              }
            ]
          }
        ]
      },
      "runs": [
        {
          "textPreview": "Experience",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "b",
                "attributes": {
                  "val": "0"
                },
                "children": []
              },
              {
                "tag": "bCs",
                "attributes": {
                  "val": "0"
                },
                "children": []
              },
              {
                "tag": "color",
                "attributes": {
                  "val": "000000"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "30"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "30"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        }
      ]
    },
    {
      "paragraphIndex": 13,
      "label": "QA Lead / Senior Quality Assurance Engineer | Möbel Pfister AGApril 2023 – July 2026 | Rem",
      "paragraphProperties": {
        "tag": "pPr",
        "attributes": {},
        "children": [
          {
            "tag": "keepNext",
            "attributes": {
              "val": "1"
            },
            "children": []
          },
          {
            "tag": "spacing",
            "attributes": {
              "after": "40",
              "before": "80",
              "line": "360",
              "lineRule": "auto"
            },
            "children": []
          },
          {
            "tag": "ind",
            "attributes": {
              "right": "54"
            },
            "children": []
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              }
            ]
          }
        ]
      },
      "runs": [
        {
          "textPreview": "QA Lead / Senior Quality Assurance Engineer | Möbel Pfister AG",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "b",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "bCs",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "26"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "26"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        },
        {
          "textPreview": "April 2023 – July 2026 | Remote",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "b",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "bCs",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "24"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "24"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": [
            {
              "tag": "br",
              "attributes": {
                "type": "textWrapping"
              },
              "children": []
            }
          ]
        },
        {
          "textPreview": "",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        }
      ]
    },
    {
      "paragraphIndex": 14,
      "label": "Led quality delivery across 2 interconnected systems and 4–5 production releases per month",
      "paragraphProperties": {
        "tag": "pPr",
        "attributes": {},
        "children": [
          {
            "tag": "keepLines",
            "attributes": {
              "val": "1"
            },
            "children": []
          },
          {
            "tag": "numPr",
            "attributes": {},
            "children": [
              {
                "tag": "ilvl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              },
              {
                "tag": "numId",
                "attributes": {
                  "val": "1"
                },
                "children": []
              }
            ]
          },
          {
            "tag": "spacing",
            "attributes": {
              "line": "360",
              "lineRule": "auto"
            },
            "children": []
          },
          {
            "tag": "ind",
            "attributes": {
              "right": "54",
              "firstLine": "425.19685039370086"
            },
            "children": []
          },
          {
            "tag": "jc",
            "attributes": {
              "val": "both"
            },
            "children": []
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              }
            ]
          }
        ]
      },
      "runs": [
        {
          "textPreview": "Led quality delivery across 2 interconnected systems and 4–5 productio",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        }
      ]
    },
    {
      "paragraphIndex": 15,
      "label": "Managed and developed a 5-person QA team through goal setting, 1:1s, performance reviews, ",
      "paragraphProperties": {
        "tag": "pPr",
        "attributes": {},
        "children": [
          {
            "tag": "keepLines",
            "attributes": {
              "val": "1"
            },
            "children": []
          },
          {
            "tag": "numPr",
            "attributes": {},
            "children": [
              {
                "tag": "ilvl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              },
              {
                "tag": "numId",
                "attributes": {
                  "val": "1"
                },
                "children": []
              }
            ]
          },
          {
            "tag": "spacing",
            "attributes": {
              "line": "360",
              "lineRule": "auto"
            },
            "children": []
          },
          {
            "tag": "ind",
            "attributes": {
              "right": "54",
              "firstLine": "425.19685039370086"
            },
            "children": []
          },
          {
            "tag": "jc",
            "attributes": {
              "val": "both"
            },
            "children": []
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              }
            ]
          }
        ]
      },
      "runs": [
        {
          "textPreview": "Managed and developed a 5-person QA team through goal setting, 1:1s, p",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        }
      ]
    },
    {
      "paragraphIndex": 16,
      "label": "Reduced late discovery of quality risks by applying shift-left testing during requirements",
      "paragraphProperties": {
        "tag": "pPr",
        "attributes": {},
        "children": [
          {
            "tag": "keepLines",
            "attributes": {
              "val": "1"
            },
            "children": []
          },
          {
            "tag": "numPr",
            "attributes": {},
            "children": [
              {
                "tag": "ilvl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              },
              {
                "tag": "numId",
                "attributes": {
                  "val": "1"
                },
                "children": []
              }
            ]
          },
          {
            "tag": "spacing",
            "attributes": {
              "line": "360",
              "lineRule": "auto"
            },
            "children": []
          },
          {
            "tag": "ind",
            "attributes": {
              "right": "54",
              "firstLine": "425.19685039370086"
            },
            "children": []
          },
          {
            "tag": "jc",
            "attributes": {
              "val": "both"
            },
            "children": []
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              }
            ]
          }
        ]
      },
      "runs": [
        {
          "textPreview": "Reduced late discovery of quality risks by applying shift-left testing",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        }
      ]
    },
    {
      "paragraphIndex": 17,
      "label": "Increased automated regression protection for business-critical web functionality by devel",
      "paragraphProperties": {
        "tag": "pPr",
        "attributes": {},
        "children": [
          {
            "tag": "keepLines",
            "attributes": {
              "val": "1"
            },
            "children": []
          },
          {
            "tag": "numPr",
            "attributes": {},
            "children": [
              {
                "tag": "ilvl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              },
              {
                "tag": "numId",
                "attributes": {
                  "val": "1"
                },
                "children": []
              }
            ]
          },
          {
            "tag": "spacing",
            "attributes": {
              "line": "360",
              "lineRule": "auto"
            },
            "children": []
          },
          {
            "tag": "ind",
            "attributes": {
              "right": "54",
              "firstLine": "425.19685039370086"
            },
            "children": []
          },
          {
            "tag": "jc",
            "attributes": {
              "val": "both"
            },
            "children": []
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              }
            ]
          }
        ]
      },
      "runs": [
        {
          "textPreview": "Increased automated regression protection for business-critical web fu",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        }
      ]
    },
    {
      "paragraphIndex": 18,
      "label": "Protected business-critical workflows across payment integrations, REST APIs, asynchronous",
      "paragraphProperties": {
        "tag": "pPr",
        "attributes": {},
        "children": [
          {
            "tag": "keepLines",
            "attributes": {
              "val": "1"
            },
            "children": []
          },
          {
            "tag": "numPr",
            "attributes": {},
            "children": [
              {
                "tag": "ilvl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              },
              {
                "tag": "numId",
                "attributes": {
                  "val": "1"
                },
                "children": []
              }
            ]
          },
          {
            "tag": "spacing",
            "attributes": {
              "line": "360",
              "lineRule": "auto"
            },
            "children": []
          },
          {
            "tag": "ind",
            "attributes": {
              "right": "54",
              "firstLine": "425.19685039370086"
            },
            "children": []
          },
          {
            "tag": "jc",
            "attributes": {
              "val": "both"
            },
            "children": []
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              }
            ]
          }
        ]
      },
      "runs": [
        {
          "textPreview": "Protected business-critical workflows across payment integrations, RES",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        }
      ]
    },
    {
      "paragraphIndex": 19,
      "label": "Increased automated regression protection for business-critical functionality by defining ",
      "paragraphProperties": {
        "tag": "pPr",
        "attributes": {},
        "children": [
          {
            "tag": "keepLines",
            "attributes": {
              "val": "1"
            },
            "children": []
          },
          {
            "tag": "numPr",
            "attributes": {},
            "children": [
              {
                "tag": "ilvl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              },
              {
                "tag": "numId",
                "attributes": {
                  "val": "1"
                },
                "children": []
              }
            ]
          },
          {
            "tag": "spacing",
            "attributes": {
              "line": "360",
              "lineRule": "auto"
            },
            "children": []
          },
          {
            "tag": "ind",
            "attributes": {
              "right": "54",
              "firstLine": "425.19685039370086"
            },
            "children": []
          },
          {
            "tag": "jc",
            "attributes": {
              "val": "both"
            },
            "children": []
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              }
            ]
          }
        ]
      },
      "runs": [
        {
          "textPreview": "Increased automated regression protection for business-critical functi",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        }
      ]
    },
    {
      "paragraphIndex": 20,
      "label": "Improved QA workflows across requirement analysis, test case design, and bug reporting by ",
      "paragraphProperties": {
        "tag": "pPr",
        "attributes": {},
        "children": [
          {
            "tag": "keepLines",
            "attributes": {
              "val": "1"
            },
            "children": []
          },
          {
            "tag": "numPr",
            "attributes": {},
            "children": [
              {
                "tag": "ilvl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              },
              {
                "tag": "numId",
                "attributes": {
                  "val": "1"
                },
                "children": []
              }
            ]
          },
          {
            "tag": "spacing",
            "attributes": {
              "line": "360",
              "lineRule": "auto"
            },
            "children": []
          },
          {
            "tag": "ind",
            "attributes": {
              "right": "54",
              "firstLine": "425.19685039370086"
            },
            "children": []
          },
          {
            "tag": "jc",
            "attributes": {
              "val": "both"
            },
            "children": []
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              }
            ]
          }
        ]
      },
      "runs": [
        {
          "textPreview": "Improved QA workflows across requirement analysis, test case design, a",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        }
      ]
    },
    {
      "paragraphIndex": 21,
      "label": "Quality Assurance Engineer | MobiDevSeptember 2021 – March 2023 | Kharkiv, Ukraine",
      "paragraphProperties": {
        "tag": "pPr",
        "attributes": {},
        "children": [
          {
            "tag": "keepNext",
            "attributes": {
              "val": "1"
            },
            "children": []
          },
          {
            "tag": "spacing",
            "attributes": {
              "after": "40",
              "before": "140",
              "line": "360",
              "lineRule": "auto"
            },
            "children": []
          },
          {
            "tag": "ind",
            "attributes": {
              "right": "54"
            },
            "children": []
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              }
            ]
          }
        ]
      },
      "runs": [
        {
          "textPreview": "Quality Assurance Engineer | MobiDev",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "b",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "bCs",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "26"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "26"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        },
        {
          "textPreview": "September 2021 – March 2023 | Kharkiv, Ukraine",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "b",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "bCs",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "24"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "24"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": [
            {
              "tag": "br",
              "attributes": {
                "type": "textWrapping"
              },
              "children": []
            }
          ]
        },
        {
          "textPreview": "",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        }
      ]
    },
    {
      "paragraphIndex": 22,
      "label": "Improved early defect detection by applying shift-left testing during requirements analysi",
      "paragraphProperties": {
        "tag": "pPr",
        "attributes": {},
        "children": [
          {
            "tag": "keepLines",
            "attributes": {
              "val": "1"
            },
            "children": []
          },
          {
            "tag": "numPr",
            "attributes": {},
            "children": [
              {
                "tag": "ilvl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              },
              {
                "tag": "numId",
                "attributes": {
                  "val": "1"
                },
                "children": []
              }
            ]
          },
          {
            "tag": "spacing",
            "attributes": {
              "line": "360",
              "lineRule": "auto"
            },
            "children": []
          },
          {
            "tag": "ind",
            "attributes": {
              "right": "54",
              "firstLine": "425.19685039370086"
            },
            "children": []
          },
          {
            "tag": "jc",
            "attributes": {
              "val": "both"
            },
            "children": []
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              }
            ]
          }
        ]
      },
      "runs": [
        {
          "textPreview": "Improved early defect detection by applying shift-left testing during ",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        }
      ]
    },
    {
      "paragraphIndex": 23,
      "label": "Increased confidence in data consistency across 2 interconnected systems by testing cross-",
      "paragraphProperties": {
        "tag": "pPr",
        "attributes": {},
        "children": [
          {
            "tag": "keepLines",
            "attributes": {
              "val": "1"
            },
            "children": []
          },
          {
            "tag": "numPr",
            "attributes": {},
            "children": [
              {
                "tag": "ilvl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              },
              {
                "tag": "numId",
                "attributes": {
                  "val": "1"
                },
                "children": []
              }
            ]
          },
          {
            "tag": "spacing",
            "attributes": {
              "line": "360",
              "lineRule": "auto"
            },
            "children": []
          },
          {
            "tag": "ind",
            "attributes": {
              "right": "54",
              "firstLine": "425.19685039370086"
            },
            "children": []
          },
          {
            "tag": "jc",
            "attributes": {
              "val": "both"
            },
            "children": []
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              }
            ]
          }
        ]
      },
      "runs": [
        {
          "textPreview": "Increased confidence in data consistency across 2 interconnected syste",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        }
      ]
    },
    {
      "paragraphIndex": 24,
      "label": "Strengthened integration coverage by validating positive, negative, duplicate, delayed, an",
      "paragraphProperties": {
        "tag": "pPr",
        "attributes": {},
        "children": [
          {
            "tag": "keepLines",
            "attributes": {
              "val": "1"
            },
            "children": []
          },
          {
            "tag": "numPr",
            "attributes": {},
            "children": [
              {
                "tag": "ilvl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              },
              {
                "tag": "numId",
                "attributes": {
                  "val": "1"
                },
                "children": []
              }
            ]
          },
          {
            "tag": "spacing",
            "attributes": {
              "line": "360",
              "lineRule": "auto"
            },
            "children": []
          },
          {
            "tag": "ind",
            "attributes": {
              "right": "54",
              "firstLine": "425.19685039370086"
            },
            "children": []
          },
          {
            "tag": "jc",
            "attributes": {
              "val": "both"
            },
            "children": []
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              }
            ]
          }
        ]
      },
      "runs": [
        {
          "textPreview": "Strengthened integration coverage by validating positive, negative, du",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        }
      ]
    },
    {
      "paragraphIndex": 25,
      "label": "Improved product quality across web, Android, and iOS applications by executing functional",
      "paragraphProperties": {
        "tag": "pPr",
        "attributes": {},
        "children": [
          {
            "tag": "keepLines",
            "attributes": {
              "val": "1"
            },
            "children": []
          },
          {
            "tag": "numPr",
            "attributes": {},
            "children": [
              {
                "tag": "ilvl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              },
              {
                "tag": "numId",
                "attributes": {
                  "val": "1"
                },
                "children": []
              }
            ]
          },
          {
            "tag": "spacing",
            "attributes": {
              "line": "360",
              "lineRule": "auto"
            },
            "children": []
          },
          {
            "tag": "ind",
            "attributes": {
              "right": "54",
              "firstLine": "425.19685039370086"
            },
            "children": []
          },
          {
            "tag": "jc",
            "attributes": {
              "val": "both"
            },
            "children": []
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              }
            ]
          }
        ]
      },
      "runs": [
        {
          "textPreview": "Improved product quality across web, Android, and iOS applications by ",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        }
      ]
    },
    {
      "paragraphIndex": 26,
      "label": "Reduced investigation time for critical defects by analysing API behaviour, browser DevToo",
      "paragraphProperties": {
        "tag": "pPr",
        "attributes": {},
        "children": [
          {
            "tag": "keepLines",
            "attributes": {
              "val": "1"
            },
            "children": []
          },
          {
            "tag": "numPr",
            "attributes": {},
            "children": [
              {
                "tag": "ilvl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              },
              {
                "tag": "numId",
                "attributes": {
                  "val": "1"
                },
                "children": []
              }
            ]
          },
          {
            "tag": "spacing",
            "attributes": {
              "line": "360",
              "lineRule": "auto"
            },
            "children": []
          },
          {
            "tag": "ind",
            "attributes": {
              "right": "54",
              "firstLine": "425.19685039370086"
            },
            "children": []
          },
          {
            "tag": "jc",
            "attributes": {
              "val": "both"
            },
            "children": []
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              }
            ]
          }
        ]
      },
      "runs": [
        {
          "textPreview": "Reduced investigation time for critical defects by analysing API behav",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        },
        {
          "textPreview": "",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        }
      ]
    },
    {
      "paragraphIndex": 27,
      "label": "Quality Assurance Engineer | NearShorePartner.chFebruary 2019 – August 2021 | Kharkiv, Ukr",
      "paragraphProperties": {
        "tag": "pPr",
        "attributes": {},
        "children": [
          {
            "tag": "keepNext",
            "attributes": {
              "val": "1"
            },
            "children": []
          },
          {
            "tag": "spacing",
            "attributes": {
              "after": "40",
              "before": "140",
              "line": "360",
              "lineRule": "auto"
            },
            "children": []
          },
          {
            "tag": "ind",
            "attributes": {
              "right": "54"
            },
            "children": []
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "b",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "bCs",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "24"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "24"
                },
                "children": []
              }
            ]
          }
        ]
      },
      "runs": [
        {
          "textPreview": "Q",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "b",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "bCs",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "24"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "24"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        },
        {
          "textPreview": "uality Assurance Engineer | ",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "b",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "bCs",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "26"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "26"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        },
        {
          "textPreview": "NearShorePartner.ch",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "b",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "bCs",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "26"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "26"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": [
            {
              "tag": "br",
              "attributes": {
                "type": "textWrapping"
              },
              "children": []
            }
          ]
        },
        {
          "textPreview": "February 2019 – August 2021 | Kharkiv, Ukraine",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "b",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "bCs",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "24"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "24"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        }
      ]
    },
    {
      "paragraphIndex": 28,
      "label": "Improved product quality across web and mobile applications by executing functional, non-f",
      "paragraphProperties": {
        "tag": "pPr",
        "attributes": {},
        "children": [
          {
            "tag": "keepLines",
            "attributes": {
              "val": "1"
            },
            "children": []
          },
          {
            "tag": "numPr",
            "attributes": {},
            "children": [
              {
                "tag": "ilvl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              },
              {
                "tag": "numId",
                "attributes": {
                  "val": "1"
                },
                "children": []
              }
            ]
          },
          {
            "tag": "spacing",
            "attributes": {
              "line": "360",
              "lineRule": "auto"
            },
            "children": []
          },
          {
            "tag": "ind",
            "attributes": {
              "right": "54",
              "firstLine": "425.19685039370086"
            },
            "children": []
          },
          {
            "tag": "jc",
            "attributes": {
              "val": "both"
            },
            "children": []
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "20"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "20"
                },
                "children": []
              }
            ]
          }
        ]
      },
      "runs": [
        {
          "textPreview": "Improved product quality across web and mobile applications by executi",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        }
      ]
    },
    {
      "paragraphIndex": 29,
      "label": "Strengthened API and system integration coverage by testing REST services with Postman and",
      "paragraphProperties": {
        "tag": "pPr",
        "attributes": {},
        "children": [
          {
            "tag": "keepLines",
            "attributes": {
              "val": "1"
            },
            "children": []
          },
          {
            "tag": "numPr",
            "attributes": {},
            "children": [
              {
                "tag": "ilvl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              },
              {
                "tag": "numId",
                "attributes": {
                  "val": "1"
                },
                "children": []
              }
            ]
          },
          {
            "tag": "spacing",
            "attributes": {
              "line": "360",
              "lineRule": "auto"
            },
            "children": []
          },
          {
            "tag": "ind",
            "attributes": {
              "right": "54",
              "firstLine": "425.19685039370086"
            },
            "children": []
          },
          {
            "tag": "jc",
            "attributes": {
              "val": "both"
            },
            "children": []
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "20"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "20"
                },
                "children": []
              }
            ]
          }
        ]
      },
      "runs": [
        {
          "textPreview": "Strengthened API and system integration coverage by testing REST servi",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        }
      ]
    },
    {
      "paragraphIndex": 30,
      "label": "Improved test coverage and regression consistency by creating, executing, and maintaining ",
      "paragraphProperties": {
        "tag": "pPr",
        "attributes": {},
        "children": [
          {
            "tag": "keepLines",
            "attributes": {
              "val": "1"
            },
            "children": []
          },
          {
            "tag": "numPr",
            "attributes": {},
            "children": [
              {
                "tag": "ilvl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              },
              {
                "tag": "numId",
                "attributes": {
                  "val": "1"
                },
                "children": []
              }
            ]
          },
          {
            "tag": "spacing",
            "attributes": {
              "line": "360",
              "lineRule": "auto"
            },
            "children": []
          },
          {
            "tag": "ind",
            "attributes": {
              "right": "54",
              "firstLine": "425.19685039370086"
            },
            "children": []
          },
          {
            "tag": "jc",
            "attributes": {
              "val": "both"
            },
            "children": []
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              }
            ]
          }
        ]
      },
      "runs": [
        {
          "textPreview": "Improved test coverage and regression consistency by creating, executi",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        },
        {
          "textPreview": "",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        }
      ]
    },
    {
      "paragraphIndex": 31,
      "label": "Education",
      "paragraphProperties": {
        "tag": "pPr",
        "attributes": {},
        "children": [
          {
            "tag": "pStyle",
            "attributes": {
              "val": "Heading2"
            },
            "children": []
          },
          {
            "tag": "keepNext",
            "attributes": {
              "val": "1"
            },
            "children": []
          },
          {
            "tag": "pBdr",
            "attributes": {},
            "children": [
              {
                "tag": "bottom",
                "attributes": {
                  "color": "000000",
                  "space": "4",
                  "sz": "12",
                  "val": "single"
                },
                "children": []
              }
            ]
          },
          {
            "tag": "spacing",
            "attributes": {
              "after": "160",
              "before": "160",
              "line": "276",
              "lineRule": "auto"
            },
            "children": []
          },
          {
            "tag": "ind",
            "attributes": {
              "right": "54"
            },
            "children": []
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "b",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "bCs",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "24"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "24"
                },
                "children": []
              }
            ]
          },
          {
            "tag": "sectPr",
            "attributes": {},
            "children": [
              {
                "tag": "type",
                "attributes": {
                  "val": "continuous"
                },
                "children": []
              },
              {
                "tag": "pgSz",
                "attributes": {
                  "h": "16840",
                  "w": "11900",
                  "orient": "portrait"
                },
                "children": []
              },
              {
                "tag": "pgMar",
                "attributes": {
                  "bottom": "566.9291338582677",
                  "top": "566.9291338582677",
                  "left": "737.0078740157481",
                  "right": "737.0078740157481",
                  "header": "720",
                  "footer": "720"
                },
                "children": []
              }
            ]
          }
        ]
      },
      "runs": [
        {
          "textPreview": "Education",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "b",
                "attributes": {
                  "val": "0"
                },
                "children": []
              },
              {
                "tag": "bCs",
                "attributes": {
                  "val": "0"
                },
                "children": []
              },
              {
                "tag": "color",
                "attributes": {
                  "val": "000000"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "32"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "32"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        },
        {
          "textPreview": "",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        }
      ]
    },
    {
      "paragraphIndex": 32,
      "label": "Kharkiv National University of RadioelectronicsMSc, Software Engineering — 2020BSc, Softwa",
      "paragraphProperties": {
        "tag": "pPr",
        "attributes": {},
        "children": [
          {
            "tag": "spacing",
            "attributes": {
              "after": "240",
              "line": "276",
              "lineRule": "auto"
            },
            "children": []
          },
          {
            "tag": "ind",
            "attributes": {
              "right": "54"
            },
            "children": []
          },
          {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "b",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "bCs",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              }
            ]
          }
        ]
      },
      "runs": [
        {
          "textPreview": "Kharkiv National University of Radioelectronics",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "b",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "bCs",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "24"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "24"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": [
            {
              "tag": "br",
              "attributes": {
                "type": "textWrapping"
              },
              "children": []
            }
          ]
        },
        {
          "textPreview": "MSc, Software Engineering — 2020BSc, Software Engineering — 2018",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "24"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "24"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": [
            {
              "tag": "br",
              "attributes": {
                "type": "textWrapping"
              },
              "children": []
            }
          ]
        },
        {
          "textPreview": "Certification:",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "b",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "bCs",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": [
            {
              "tag": "br",
              "attributes": {
                "type": "textWrapping"
              },
              "children": []
            }
          ]
        },
        {
          "textPreview": " ISTQB Certified Tester Foundation Level (CTFL), 2020",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": [
            {
              "tag": "br",
              "attributes": {
                "type": "textWrapping"
              },
              "children": []
            }
          ]
        },
        {
          "textPreview": "Domains:",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "b",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "bCs",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        },
        {
          "textPreview": " E-commerce, SaaS, Healthcare",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": [
            {
              "tag": "br",
              "attributes": {
                "type": "textWrapping"
              },
              "children": []
            }
          ]
        },
        {
          "textPreview": "Languages:",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "b",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "bCs",
                "attributes": {
                  "val": "1"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        },
        {
          "textPreview": " English (C1), Ukrainian (Native)",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rFonts",
                "attributes": {
                  "ascii": "Raleway",
                  "cs": "Raleway",
                  "eastAsia": "Raleway",
                  "hAnsi": "Raleway"
                },
                "children": []
              },
              {
                "tag": "sz",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "szCs",
                "attributes": {
                  "val": "22"
                },
                "children": []
              },
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        },
        {
          "textPreview": "",
          "properties": {
            "tag": "rPr",
            "attributes": {},
            "children": [
              {
                "tag": "rtl",
                "attributes": {
                  "val": "0"
                },
                "children": []
              }
            ]
          },
          "breaks": []
        }
      ]
    }
  ]
}
```
