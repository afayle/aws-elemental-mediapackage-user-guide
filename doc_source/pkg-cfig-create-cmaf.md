# Creating a Common Media Application Format \(CMAF\) Packaging Configuration<a name="pkg-cfig-create-cmaf"></a>

Create a packaging configuration that formats content for devices that support Apple HLS fragmented MP4 \(fMP4\)\.

**To create a CMAF packaging configuration \(console\)**

1. Open the MediaPackage console at [https://console\.aws\.amazon\.com/mediapackage/](https://console.aws.amazon.com/mediapackage/)\.

1. In the navigation pane, under **Video on demand**, choose **Packaging groups**\.

1. On the **Packaging groups** page, choose the group that will contain the configuration that you're creating\.

1. On the details page for the packaging group, in the **Packaging configurations** section, choose **Add or remove configs**\.

1. On the **Add or remove packaging configurations** page, in the **Packaging configurations** section, choose **Add** and select **New config**\.

1. Complete the fields as described in the following topics:
   + [General Settings Fields](cfigs-cmaf-new.md)
   + [Manifest Settings Fields](cfigs-cmaf-manset.md)
   + [Stream Selection Fields](cfigs-cmaf-include-streams.md)
   + [Encryption Fields](cfigs-cmaf-encryption.md)

1. Choose **Save**\.

If you exceed the limits for your account when you're creating a packaging configuration, you get an error\. If you get an error similar to Too many requests, please try again\. Resource limit exceeded, either you have exceeded the API request limits, or you have already reached the maximum number of packaging groups allowed on your account\. If this is your first group, or if you think you mistakenly received this error, contact [AWS Support](https://aws.amazon.com/support)\. For more information about limits in MediaPackage, see [Limits in AWS Elemental MediaPackage](limits.md)\.