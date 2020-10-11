# Hello-World
This is a repository, I am creating to understand the features of github
below is rough work
{
  "$schema": "http://json-schema.org/draft-04/schema#",
  "$ref": "#/definitions/node",
  "definitions": {
    "node": {
      "properties": {
        "Id": {
          "type": "integer"
        },
        "Label": {
          "type": "string"
        },
        "Children": {
          "type": "array",
          "items": {
            "$ref": "#/definitions/node"
          }
        }
      },
      "required": [
        "Id"
      ]
    }
  }
}
{
  "lessons":[
    {
    "tutorialid":1,
    "tutorialname":"thename1",
    "tutorialdescription":"thedescription1",
    "chapters":[{
    "chapternumber":"chapter1", "chapterdescription":"chdesc1", "chapterurl":"chap1url", "childrenchapters":""
    }]
    },
    {
    "tutorialid":2,
    "tutorialname":"thename2",
    "tutorialdescription":"thedescription2",
    "chapters":[{
    "chapternumber":"chapter1", "chapterdescription":"chdesc1", "chapterurl":"chap1url", "childrenchapters":""
    }]
    }
  ]
}
