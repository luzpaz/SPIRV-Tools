use_relative_paths = True

vars = {
  'github': 'https://github.com',

  'effcee_revision': '2ec8f8738118cc483b67c04a759fee53496c5659',
  'googletest_revision': '3af06fe1664d30f98de1e78c53a7087e842a2547',
  're2_revision': 'ca11026a032ce2a3de4b3c389ee53d2bdc8794d6',
  'spirv_headers_revision': 'f027d53ded7e230e008d37c8b47ede7cd308e19d',
}

deps = {
  'external/effcee':
      Var('github') + '/google/effcee.git@' + Var('effcee_revision'),

  'external/googletest':
      Var('github') + '/google/googletest.git@' + Var('googletest_revision'),

  'external/re2':
      Var('github') + '/google/re2.git@' + Var('re2_revision'),

  'external/spirv-headers':
      Var('github') +  '/KhronosGroup/SPIRV-Headers.git@' +
          Var('spirv_headers_revision'),
}

