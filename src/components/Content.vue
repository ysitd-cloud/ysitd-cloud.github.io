<template>
  <v-layout column>
    <v-layout row class="my-2">
      <v-flex xs12>
        <v-card>
          <v-card-title primary-title>
            <div>
              <h3 class="headline">Introduction</h3>
            </div>
          </v-card-title>
          <v-card-text>
            <p>
              This is an PaaS solution built by <a href="http://ysitd.io/" target="_blank">YSITD Community</a>.
              It is using <a href="http://k8s.io/" target="_blank">Kubernetes</a> as the base platform.
            </p>
          </v-card-text>
        </v-card>
      </v-flex>
    </v-layout>
    <v-layout row class="my-2">
      <v-flex xs12>
        <v-card>
          <v-card-title primary-title>
            <div>
              <h3 class="headline">Current Status</h3>
            </div>
          </v-card-title>
          <v-card-text>It is still not yet completely open for use.</v-card-text>
        </v-card>
      </v-flex>
    </v-layout>
    <v-layout row class="my-2">
      <v-flex xs12>
        <v-card>
          <v-card-title primary-title>
            <div>
              <h3 class="headline">Development</h3>
            </div>
          </v-card-title>
          <v-card-text>
            You may checkout <a href="https://develop.ysitd.cloud">Development Status</a>
            or <a href="https://github.com/ysitd-cloud">YSITD Cloud Github</a>.
          </v-card-text>
        </v-card>
      </v-flex>
    </v-layout>
  </v-layout>
</template>
