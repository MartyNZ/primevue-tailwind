<template>
    <DocComponent title="Vue Otp Input Component" header="InputOtp" description="Input Otp is used to enter one time passwords." :componentDocs="docs" :presetDoc="presetDoc" apiLink="/inputotp/#api" ptLink="/inputotp/#pt" />
</template>

<script>
import AccessibilityDoc from '@/doc/inputotp/AccessibilityDoc.vue';
import BasicDoc from '@/doc/inputotp/BasicDoc.vue';
import FilledDoc from '@/doc/inputotp/FilledDoc.vue';
import FormsDoc from '@/doc/inputotp/FormsDoc.vue';
import ImportDoc from '@/doc/inputotp/ImportDoc.vue';
import IntegerOnlyDoc from '@/doc/inputotp/IntegerOnlyDoc.vue';
import MaskDoc from '@/doc/inputotp/MaskDoc.vue';
import SampleDoc from '@/doc/inputotp/SampleDoc.vue';
import SizesDoc from '@/doc/inputotp/SizesDoc.vue';
import TemplateDoc from '@/doc/inputotp/TemplateDoc.vue';

export default {
    data() {
        return {
            docs: [
                {
                    id: 'import',
                    label: 'Import',
                    component: ImportDoc
                },
                {
                    id: 'basic',
                    label: 'Basic',
                    component: BasicDoc
                },
                {
                    id: 'forms',
                    label: 'Forms',
                    component: FormsDoc
                },
                {
                    id: 'mask',
                    label: 'Mask',
                    component: MaskDoc
                },
                {
                    id: 'integeronly',
                    label: 'Integer Only',
                    component: IntegerOnlyDoc
                },
                {
                    id: 'filled',
                    label: 'Filled',
                    component: FilledDoc
                },
                {
                    id: 'sizes',
                    label: 'Sizes',
                    component: SizesDoc
                },
                {
                    id: 'template',
                    label: 'Template',
                    component: TemplateDoc
                },
                {
                    id: 'sample',
                    label: 'Sample',
                    component: SampleDoc
                },
                {
                    id: 'accessibility',
                    label: 'Accessibility',
                    component: AccessibilityDoc
                }
            ],
            presetDoc: {
                key: 'inputotp'
            }
        };
    }
};
</script>
