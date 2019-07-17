@Library('pipeline-shared@cdn-pipeline') _

cloudFrontDeliveryPipeline([
        projectName: "product-search",
        builderImage: "node:8.16.0-jessie",
        s3Bucket: "ekomi-cdn-coupons-prod",
       	cloudFrontDistributionID: "E1RSWIP0CB9HH2",
       	buildCommand: "npm install && npm audit fix && npm run react-scripts build",
        environmentVariables: [
            APP_URL: "http://something.com",
            BASE_SOMETHING: "whatever."
        ]
    ]
)
