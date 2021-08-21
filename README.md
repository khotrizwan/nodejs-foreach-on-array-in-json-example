<p># nodejs-foreach-on-array-in-json-example</p>

<p>This is a sample example.</p> 
<p>In this example, will find if the data->linesOfInsurance->coveragePartCoverage->coveragePartCoverageScheduleItem element is present or not for the case 
if data->linesOfInsurance->coveragePartCoverage->coveragePurchaseCd->value is "FREEFRMP"</p>

<p>Below is the sample JSON used in this example</p>
<pre>
{
	"data": {
		"version": "1",
		"ID": "1",
		"tType": {
			"value": "NB"
		},
		"linesOfInsurance": [{
			"coveragePartCd": {
				"value": "UMB"
			},
			"coveragePartCoverage": [{
					"coveragePurchaseCd": {
						"value": "FREEFRMP"
					},
					"cn": {
						"value": "FREE FORM/MANUSCRIPT"
					},
					"coveragePartCoverageScheduleItem": [{
						"seqNo": {
							"value": "1"
						},
						"loiCdr": {
							"value": "UM"
						}
					}]
				},
				{
					"coveragePurchaseCd": {
						"value": "FREEFRMP"
					},
					"cn": {
						"value": "FREE FORM/MANUSCRIPT"
					},
					"nonCoveragePartCoverageScheduleItem": [{
						"seqNo": {
							"value": "1"
						},
						"loiCdr": {
							"value": "UM"
						}
					}]
				},
				{
					"coveragePurchaseCd": {
						"value": "FREEFRMG"
					},
					"cn": {
						"value": "FREE FORM/MANUSCRIPT"
					},
					"coveragePartCoverageScheduleItem": [{
						"seqNo": {
							"value": "1"
						},
						"loiCdr": {
							"value": "UM"
						}
					}]
				}
			]
		}]
	}
}
</pre>
