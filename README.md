# snippets-react-native-nlw
```js
{
	"Basic React Native Component": {
		"prefix": "rnbc",
		"body": [
			"import React from 'react';",
			"",
			"import {",
			"  View",
			"} from 'react-native';",
			"",
			"import { styles } from './styles';",
			"",
			"export function ${TM_DIRECTORY/^.+\\/(.*)$/$1/}(){",
			"  return (",
			"    <View>",
			"",
			"    </View>",
			"  );",
			"}"
		],
		"description": "Create the structure of a react native component"
	},

	"StyleSheet React Native Object": {
		"prefix": "rnso",
		"body": [
			"import { StyleSheet } from 'react-native';",
			"",
			"export const styles = StyleSheet.create({",
			"  container: {",
			"    flex: 1,",			
			"  }",			
			"});"
		],
		"description": "Create a style object with Stylesheet to separate file."
	}
}

```