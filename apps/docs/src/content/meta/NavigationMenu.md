<!-- This file was automatic generated. Do not edit it manually -->

<PropsTable :data="[
  {
    'name': 'as',
    'description': '<p>The element or component this component should render as. Can be overwrite by <code>asChild</code></p>\n',
    'type': 'AsTag | Component',
    'required': false,
    'default': '\'div\''
  },
  {
    'name': 'asChild',
    'description': '<p>Change the default rendered element for the one passed as a child, merging their props and behavior.</p>\n<p>Read our <a href=\'https://www.radix-vue.com/guides/composition.html\'>Composition</a> guide for more details.</p>\n',
    'type': 'boolean',
    'required': false
  },
  {
    'name': 'defaultValue',
    'description': '<p>The value of the menu item that should be active when initially rendered.</p>\n<p>Use when you do not need to control the value state.</p>\n',
    'type': 'string',
    'required': false
  },
  {
    'name': 'delayDuration',
    'description': '<p>The duration from when the pointer enters the trigger until the tooltip gets opened.</p>\n',
    'type': 'number',
    'required': false
  },
  {
    'name': 'dir',
    'description': '<p>The reading direction of the combobox when applicable.</p>\n<p>If omitted, inherits globally from <code>DirectionProvider</code> or assumes LTR (left-to-right) reading mode.</p>\n',
    'type': '\'ltr\' | \'rtl\'',
    'required': false
  },
  {
    'name': 'disableClickTrigger',
    'description': '<p>If <code>true</code>, menu cannot be open by click on trigger</p>\n',
    'type': 'boolean',
    'required': false
  },
  {
    'name': 'disableHoverTrigger',
    'description': '<p>If <code>true</code>, menu cannot be open by hover on trigger</p>\n',
    'type': 'boolean',
    'required': false
  },
  {
    'name': 'modelValue',
    'description': '<p>The controlled value of the menu item to activate. Can be used as <code>v-model</code>.</p>\n',
    'type': 'string',
    'required': false
  },
  {
    'name': 'orientation',
    'description': '<p>The orientation of the menu.</p>\n',
    'type': '\'vertical\' | \'horizontal\'',
    'required': false
  },
  {
    'name': 'skipDelayDuration',
    'description': '<p>How much time a user has to enter another trigger without incurring a delay again.</p>\n',
    'type': 'number',
    'required': false
  }
]" />

<EmitsTable :data="[
  {
    'name': 'update:modelValue',
    'description': '',
    'type': '[value: string]'
  }
]" />
