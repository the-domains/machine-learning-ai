---
isBasedOnUrl: 'https://www.tensorflow.org/hub/'
keywords: []
title: TensorFlow Hub | TensorFlow
dateModified: '2018-04-02T05:14:14.237Z'
publisher:
  name: TensorFlow
  domain: www.tensorflow.org
  url: 'https://www.tensorflow.org'
  favicon: 'https://www.tensorflow.org/_static/c82c5da5ff/images/tensorflow/favicon.png'
author: []
inFeed: true
description: >-
  import tensorflow as tf import tensorflow_hub as hub with
  tf.Graph().as_default(): embed =
  hub.Module("https://tfhub.dev/google/nnlm-en-dim128-with-normalization/1")
  embeddings = embed(["A long sentence.", "single-word", "http://example.com"])
  with tf.Session() as sess: sess.run(tf.global_variables_initializer())
  sess.run(tf.tables_initializer()) print(sess.run(embeddings))
via: {}
datePublished: '2018-04-02T05:14:15.306Z'
starred: true
datePublishedOriginal: '2018-04-02T05:14:15.306Z'
sourcePath: _posts/2018-04-02-tensorflow-hub-or-tensorflow.md
_type: MediaObject
_context: 'http://schema.org'

---
<article style=""><h1>TensorFlow Hub | TensorFlow</h1><p>import tensorflow as tf import tensorflow_hub as hub with tf.Graph().as_default(): embed = hub.Module("https://tfhub.dev/google/nnlm-en-dim128-with-normalization/1") embeddings = embed(["A long sentence.", "single-word", "http://example.com"]) with tf.Session() as sess: sess.run(tf.global_variables_initializer()) sess.run(tf.tables_initializer()) print(sess.run(embeddings))</p><img src="https://www.tensorflow.org/images/tf_logo_social.png" /></article>