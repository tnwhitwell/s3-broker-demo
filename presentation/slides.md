PaaS S3 Broker
===

---

## S3 is here!

----

(In private beta)

---

## Current functionality
* Provision private S3 buckets
* Bind them to apps
* Store your objects
* Delete your buckets

---

A single set of credentials are configured per-binding, and removing the binding will remove that binding's user from the bucket.

---

Credentials to access the bucket are provided through an environment variable

----

`$VCAP_SERVICES`:

```json
{
   "aws-s3-bucket":[
      {
         "binding_name":null,
         "credentials":{
            "aws_access_key_id":"AKIAIS4KD5RHLAAUF4SQ",
            "aws_region":"eu-west-2",
            "aws_secret_access_key":"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",
            "bucket_name":"paas-s3-broker-prod-lon-b0fcab72-7e3b-452d-8f32-ade4e00b5464",
            "deploy_env":""
         },
         "instance_name":"demo-s3",
         "label":"aws-s3-bucket",
         "name":"demo-s3",
         "plan":"default",
         "provider":null,
         "syslog_drain_url":null,
         "tags":["s3"],
         "volume_mounts":[]
      }
   ]
}
```

---

# Demo

## (🤞)

---

# FAQ

----

>That looks awesome - can I join the Beta?!??!11?

<span> Yes! Speak to the team on #paas, or wander over!<!-- .element: class="fragment" data-fragment-index="2" --></span>

---

# Questions?

---

<!-- .slide: data-background="https://media.giphy.com/media/33E7ZjlQEMgF6kbkhY/giphy.gif" -->
