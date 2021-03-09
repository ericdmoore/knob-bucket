# knob-bucket
Knob Bucket - turning S3 Buckets into memfs Volumes since 2021



API

`load(s3c: S3Client, bucket:string) => memfs.Volume`
`load(s3c: S3Client, bucket:string, v: memfs.Volume) => memfs.Volume`



`lazyLoad(s3c, bucket)=> Proxy(Volume)`
`lazyLoad(s3c, bucket, v?:vol)=> Volume(Volume)`
