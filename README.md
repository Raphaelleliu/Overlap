# Overlap
Two datasets contain business names and their addresses. Find the businesses that are common to both datasets,
Since the business names and addresses don't align perfectly between these datasets, you will
need to develop an algorithm that can find approximate matches. When your algorithm runs, it
should produce a list of triplets consisting of the entity_id from the left dataset, the business_id
from the right dataset, and a confidence score. The confidence score should have values
between 0 and 1.0 and convey a sense of confidence of the match. An identical match should
have a score of 1.0.
Your submission should consist of matches that have a high degree of confidence, eg greater
than 0.8.
