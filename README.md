# json-schema

A JSON Schema viewer React component

Explore the components: Storybook
View the changelog: Releases
Features
Full JSON Schema Draft 4 support, including oneOf and anyOf combiner properties
Renders complicated nested objects to any depth
Renders validation properties and markdown descriptions
Capable of linking resolved $refs
Theme-able
Collapsible
Installation
Supported in modern browsers and node.

# latest stable
yarn add @stoplight/json-schema-viewer
Usage
// index.jsx
import { JsonSchemaViewer } from "@stoplight/json-schema-viewer";

<JsonSchemaViewer
  name="Todos Model"
  schema={schema}
  expanded={true}
  hideTopBar={false}
  emptyText="No schema defined"
  defaultExpandedDepth={0}
/>;
