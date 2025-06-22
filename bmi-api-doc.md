# BMI API Documentation

## Overview
This API calculates Body Mass Index (BMI) based on height and weight.

## Endpoint

## Parameters

| Parameter | Type | Description |
|-----------|------|-------------|
| height | number | Height in cm |
| weight | number | Weight in kg |

## Example Request

```bash
curl https://metricbuddy.online/api/bmi?height=165&weight=60
{
  "bmi": 22.04,
  "category": "Normal"
}
