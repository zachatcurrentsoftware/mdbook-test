# Locations: Services, Meters & More

The Location represents the physical property where service is being delivered. It is distinct from the account in that it will remain there after the account-holder moves out. We store information that persists beyond individual accounts on the location, including Services and Meters. See below for some guides on what each of those represent.

You can think of the relationship between all these things as outlined in the diagram below. A location may have multiple services. Each of these services may be associated to a meter or not. They must be associated to a rate structure to correctly bill the customers (we will return to rate structures later).

![Location, Service, and Meter Diagram](https://colony-recorder.s3.amazonaws.com/files/2025-01-02/236b80c2-cfe2-4a48-8f24-5137de1bdbaf/File.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA2JDELI43R35HWXUZ%2F20250428%2Fus-west-1%2Fs3%2Faws4_request&X-Amz-Date=20250428T220426Z&X-Amz-Expires=3600&X-Amz-SignedHeaders=host&X-Amz-Signature=ca4460fe8e9e0507db0311dd816888e2f35c2b03964fc0b55ef73c72c6e99919)

