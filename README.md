### Snippets for my visual studio code

```
{
	// Place your snippets for javascript here. Each snippet is defined under a snippet name and has a prefix, body and 
	// description. The prefix is what is used to trigger the snippet and the body will be expanded and inserted. Possible variables are:
	// $1, $2 for tab stops, $0 for the final cursor position, and ${1:label}, ${2:another} for placeholders. Placeholders with the 
	// same ids are connected.
	// Example:
	// "Print to console": {
	// 	"prefix": "log",
	// 	"body": [
	// 		"console.log('$1');",
	// 		"$2"
	// 	],
	// 	"description": "Log output to console"
	// }
	"React Native Styles": {
		"prefix": "stles",
		"body": [
			"const styles = StyleSheet.create({",
			"    $1",
			"});"
		]
	},
	"React Native Component": {
		"prefix": "rnafc",
		"body": [
			"import React from 'react'",
			"import { StyleSheet, Text, View } from 'react-native'",
			"",
			"export const $1 = () => {",
			"  return (",
			"    <View>",
			"        <Text>$1 is working</Text>",
			"    </View>",
			"  )",
			"}",
			"",
			"const styles = StyleSheet.create({",
			"",
			"});"
		]
	},
	"Interface React Native Props": {
		"prefix": "rnprops",
		"body": [
			"interface Props extends StackScreenProps<RootStackParams, ''>{};",
		]
	},
	"Create JavaScript Function": {
		"prefix": "jsfunct",
		"body": [
			"const $1 = () => {",
			"",
			"}"
		]
	},
	"Tailwind Create Center Component": {
		"prefix": "tailcenter",
		"body": [
			"<div className='flex items-center justify-center'>",
			"	",
			"</div>"
		]
	},
	"Tailwind Create Grid Component": {
		"prefix": "tailgrid",
		"body": [
			"<div className='grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 2xl:grid-cols-5 gap-4'>",
			"	<div>1</div>",
			"	<div>2</div>",
			"	<div>3</div>",
			"</div>"
		]
	},
	"Tailwind Create Button Component": {
		"prefix": "tailbutton",
		"body": [
			"<button type='button' className='rounded py-3 px-4 text-white bg-[$1]'>",
			"	$2",
			"</button>"
		]
	},
	"Tailwind Create Form Component": {
		"prefix": "tailform",
		"body": [
			"<form onSubmit={$1} className=''",
			"	<button type='submit' className='rounded py-3 px-4 text-white bg-[$2]'>$3</button>",
			"</form>"
		]
	},
	"Next Image Component": {
		"prefix": "nextimg",
		"body": [
			"<Image",
			"	src={require('@/assets/flag-for-flag-china-svgrepo-com.svg')}",
			"	alt='$1'",
			"	width={$2}",
			"	height={$3}",
			"/>"
		]
	}
}
```
