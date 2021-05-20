# Week 2 Scripts Like A Developer

The code found in this repository is to help you learn how to script like a Developer.

...
## WIP

The code found in ´Week-2-Scripting-Like-A-Developer´ is currently a Work In Progress (WIP) and the readme will be updated when ready.

...
## PowerShell Code
The PowerShell code found in ´Week-2-Scripting-Like-A-Developer´

...
## Examples 
´´´Pwsh

import unittest

class TestS3(unittest.TestCase):
    def test_bucket_name_value(self):
        bucket = 'cloudskills92'

        self.assertEqual(bucket, 'cloudskills92')

    def test_region_value(self):
        region = 'us-east-1'

        self.assertEqual(region, 'us-east-1')

    def test_bucket_name_is_string(self):
        bucket = 'cloudskills92'

        self.assertTrue(type(bucket),str)

    def test_region_is_string(self):
        region = 'us-east-1'

        self.assertTrue(type(region),str)

if __name__ == '__main__':
    unittest.main()
´´´
