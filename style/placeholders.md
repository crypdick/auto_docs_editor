# Format placeholders  

This page explains how to format placeholders in commands, code samples, and text
strings. This page doesn't explain how to implement visual styling for placeholders, but it does
show examples of how Google developer documentation style renders placeholders as visually
distinct from other text.

Placeholders in sample code and commands represent values that the reader must replace when they use
the sample input. Placeholders in example output can also represent other values that vary. In
general, a placeholder has a descriptive name as a default value.

For example, the placeholder `PROJECT_ID` represents a project ID in sample
code, commands, and example output.

In example output, the placeholder `HTTP_RESPONSE_CODE` represents an
HTTP response code; the reader isn't expected to set this to a specific value.

## Placeholders

When you create placeholders follow this general guidance around using the letter
*x*:

* In general, don't use a single *x* or a series of *x*'s as placeholders; use a more
  informative placeholder.
* In some contexts (such as HTTP status codes), a series of *x*'s is the standard,
  so it's OK to use (for example) *xx* in those cases.

There are several ways to format placeholders, depending on whether you're
working in HTML or Markdown, or whether the placeholder is inline, in a code block, or in a
paragraph.

### Placeholders in inline text

If your sample code and command placeholders occur in a sentence, use the following formatting:

* In HTML, wrap variable placeholders by using the `var`
  element, like this:

  ```
  <code><var>PLACEHOLDER_NAME</var></code>
  ```
* In Markdown, wrap inline placeholders in backticks (`), and use an
  asterisk (\*) before the first backtick and after the second one
  (`*`PLACEHOLDER_NAME`*`).

If your placeholder does not represent a code sample or command, use the following formatting:

* In HTML, wrap placeholders by using the `var`
  element, like this:

  ```
  <var>PLACEHOLDER_NAME</var>
  ```

### Placeholders in code blocks

If your placeholders are in a block of code, use the following formatting:

* In Markdown, wrap the code block in a code fence (```). Inside a
  code fence, you can't apply formatting like bold or italic.

  ```
  PLACEHOLDER_NAME
  ```

### Placeholder text

**Use uppercase characters with underscore delimiters.**

In Markdown:

Recommended:

* `.../*API_NAME*`
* `.../*METHOD_NAME*`

If the context in which your placeholders appear makes using
uppercase characters with underscore delimiters a bad idea, use something else
that makes sense to you, but be internally consistent.

**Don't include possessive adjectives in placeholders.**

Not recommended:

* `.../<var>MY_API_NAME</var>`
* `.../<var>YOUR_API_NAME</var>`

**Note**: You can mark up command-line syntax with [brackets](/style/code-syntax#optional-arguments), [braces](/style/code-syntax#set-of-two-arguments), and [ellipses](/style/code-syntax#arguments-that-can-repeat). Don't put the
brackets, braces, or ellipses in the `var` element.

## Explain placeholders

When you use a placeholder in text or code, explain the placeholder the first time you use it.
It's not necessary to repeat the explanation in the document unless doing so might benefit the
reader—for example, in circumstances such as the following:

* Your document is lengthy.
* You've introduced several other placeholders in a long procedure.
* Your document isn't intended to be read from beginning to end.

The following is an example of a command that uses a placeholder with an explanation of that
placeholder:

```
<pre class="devsite-click-to-copy">
gcloud compute instances create <var>INSTANCE_NAME</var> \
    --metadata enable-guest-attributes=TRUE
</pre>

<p>Replace <code><var>INSTANCE_NAME</var></code> with the name that
you want your new VM instance to have.</p>

```

### Single placeholder

Use the following format for a single placeholder:

* Replace PLACEHOLDER with a description of what
  the placeholder represents.

Recommended:

1. Stream the build logs to the Google Cloud console:

   ```
   gcloud builds log --stream=BUILD_ID
   ```

   Replace `BUILD_ID` with the ID of the `WORKING` build that
   you copied in the preceding step.

### Two or more placeholders

Use the following format for two or more placeholders:

* Follow the command line with a descriptive list of the placeholders
  used in the command line. Explain what each placeholder represents
  even if the placeholder value is intuitive to you.
* Introduce this list with *Replace the following:*
* List the placeholders in the order in which they appear in the command line.
* Tag each placeholder in a code sample or command with `code` and
  `var` elements, followed by a
  [colon and a description that starts with a lowercase letter](/style/colons).
  For
  non-code samples, remove the `code` elements—for example:

  ```
  <li><code><var>INSTANCE_NAME</var></code>: description</li>
  ```
* If the description contains an example, introduce it with an *em dash* or
  *such as*—for example:

  ```
  <li><code><var>INSTANCE_NAME</var></code>: description&mdash;for example,...</li>
  ```

  ```
  <li><code><var>INSTANCE_NAME</var></code>: description, such as...</li>
  ```
* Each item in the list follows our [list style](/style/lists).

Recommended:

1. Set the maximum concurrency target for a new reservation:

   ```

       bq mk \
           --project_id=ADMIN_PROJECT_ID \
           --location=LOCATION \
           --target_job_concurrency=CONCURRENCY \
           --reservation \
           RESERVATION_NAME
   ```

   Replace the following:

   * `ADMIN_PROJECT_ID`: the project that owns the reservation
   * `LOCATION`: the location of the reservation
   * `CONCURRENCY`: the maximum concurrency target
   * `RESERVATION_NAME`: the name of the reservation

Recommended:

1. In Cloud Shell, set the environment variables:

   ```
   export ONPREM_PROJECT=ON_PREM_PROJECT_NAME \
       export ONPREM_ZONE=ZONE
   ```

   Replace the following:

   * `ON_PREM_PROJECT_NAME`: the Google Cloud project
     name for your on-premises project. You can find your project number on the
     [Dashboard](https://console.cloud.google.com/home/dashboard)
     page of the Google Cloud console.
   * `ZONE`: a [Google Cloud
     zone](/compute/docs/regions-zones#identifying_a_region_or_zone) that's close to your location—for example, `us-east1`.

### Placeholders in output

If you provide a code output example, explain any placeholders that appear in
sample output:

* Use `var` elements to identify the placeholder text in
  the output.
* Follow the example output with a list of the placeholders used in the
  example.
* Introduce the list of placeholders with *This output includes the
  following values:*
* List the placeholders in the order in which they appear in the
  example.
* Tag each placeholder with a `var` element,
  followed by a colon and a description that starts with a lowercase letter—for example:

  ```
  <li><code><var>INSTANCE_NAME</var></code>: description</li>
  ```
* If the description contains an example, introduce it with an *em dash* or
  *such as*—for example:

  ```
  <li><code><var>INSTANCE_NAME</var></code>: description&mdash;for example,...</li>
  ```

  ```
  <li><code><var>INSTANCE_NAME</var></code>: description, such as...</li>
  ```

Recommended:

#### Response

The output is similar to the following:

```

{
 "name": "operations/build/PROJECT_ID/OPERATION_ID",
 "metadata": {
  "@type": "type.googleapis.com/google.devtools.cloudbuild.v1.BuildOperationMetadata",
  "build": {
   "id": "BUILD_ID",
   "status": "QUEUED",
   "createTime": "2019-09-20T15:55:29.353258929Z",
   "steps": [
    {
     "name": "gcr.io/compute-image-tools/gce_vm_image_import:release",
     "env": [
      "BUILD_ID=BUILD_ID"
     ],
     "args": [
      "-timeout=7056s",
      "-image_name=IMAGE_NAME",
      "-client_id=api",
      "-data-disk",
      "-source_file=SOURCE_FILE"
     ]
    }
   ],
   "timeout": "7200s",
   "projectId": "PROJECT_ID",
   "logsBucket": "gs://PROJECT_NUMBER.cloudbuild-logs.googleusercontent.com",
   "options": {
    "logging": "LEGACY"
   },
   "logUrl": "https://console.cloud.google.com/gcr/builds/BUILD_ID?project=PROJECT_NUMBER"
  }
 }
}

```

This output includes the following values:

* `PROJECT_ID`: the project ID for the project that
  the image was imported into
* `OPERATION_ID`: the ID of the import operation
* `BUILD_ID`: the ID of the build for the import
  operation
* `IMAGE_NAME`: the name of the image to be
  imported
* `SOURCE_FILE`: the URI for the image in Cloud
  Storage—for example, `gs://my-bucket/my-image.vmdk`
* `PROJECT_NUMBER`: the number for the import
  project
