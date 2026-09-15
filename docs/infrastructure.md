# AMD Infrastructure Notes

## AMD Developer Cloud credit

Status: **REQUEST SUBMITTED / AWAITING VALIDATION**

On 2026-09-14, the AMD AI Developer Program cloud-credit request was submitted for **AMD Developer Cloud — Direct GPU Access**.

The member benefit advertised at request time was **$100 AMD Developer Cloud credit**. The member-perks page stated a 30-day expiration after activation.

AMD's confirmation stated that activation instructions should arrive by email after account validation, normally within 3 business days, with possible delay due to high demand. It advised contacting `devcloudrequests@amd.com` if cloud credits had not arrived within 5 business days.

## Intended use

Use AMD Developer Cloud for genuine AMD Instinct / ROCm-backed learning and experiments, including autonomous AI workload execution relevant to the Academy project.

## Activation discipline

- Do not mark credit ACTIVE until activation is independently confirmed.
- Avoid unnecessarily starting the limited activation window before useful work is ready.
- Record exact activation date and authoritative expiration date from the award/activation email.
- Record actual GPU/runtime/framework used for each meaningful experiment.

## Cost / resource controls

Before provisioning paid or credit-consuming resources:

- verify current pricing and quota behavior;
- verify whether stopped/powered-off resources continue consuming credit;
- determine the exact action required to stop billing/credit consumption;
- preserve work outside ephemeral compute where appropriate;
- avoid adding a payment method unless deliberately required and understood;
- destroy unused GPU resources when the platform requires destruction to stop consumption.

## Evidence template

For each material AMD workload, record:

- date;
- AMD service/environment;
- GPU type if exposed;
- ROCm/runtime version;
- framework/model;
- workload purpose;
- reproducible invocation/configuration reference;
- observed result;
- failures/friction;
- approximate resource/credit impact where available.
