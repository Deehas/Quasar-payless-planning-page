<template>
  <q-page>
    <div class="q-pa-md items-start">
      <div class="row">
        <div class="col-12 col-md">
          <div class="q-pa-md">
            <q-card class="my-card q-pa-sm" style="height:300px;">
              <q-card-section>
                <div style="height:40px">
                  <i class="fa-solid fa-circle-dot fa-2xl" style="color:#F67402;"></i>
                </div>
                <div>
                  <p class="text-h5 text-weight-bold">Basic</p>
                </div>
                <div>
                  <p>There are some limitations that maybe annoying.</p>
                </div>
                <div>
                  <span class="price text-h4 text-weight-bold">$99.99</span>
                  <span>/year</span>
                </div>
                <div>
                  <p>2% + $0.30 per transaction</p>
                </div>
                <div>
                  <q-btn push color="primary" label="Try for free 14 days"/>
                </div>
              </q-card-section>
            </q-card>
          </div>
        </div>
        <div class="col-12 col-md">
          <div class="q-py-md">
            <q-card class="my-card q-pa-sm" style="height:300px;">
              <q-card-section>
                <div class="row justify-between">
                  <div>
                    <i class="fa-solid fa-circle-dot fa-2xl" style="color:#01EEBE;"></i>
                  </div>
                  <div class="row justify-around" style="background-color:#F0F5FF;">
                    <p style="color:#035EFE;">Recomended</p>
                    <i class="fa-solid fa-thumbs-up" style="color:#035EFE;"></i>
                  </div>
                </div>
                <div>
                  <p class="text-h5 text-weight-bold">Pro</p>
                </div>
                <div>
                  <p>Enjoy many features that fit for helping your business.</p>
                </div>
                <div>
                  <span class="price text-h4 text-weight-bold">$299.99</span>
                  <span>/year</span>
                </div>
                <div>
                  <p>2.5% + $0.30 per transaction</p>
                </div>
                <div>
                  <q-btn class="disabled" label="Your Current Plan"/>
                </div>
              </q-card-section>
            </q-card>
          </div>
        </div>
        <div class="col-12 col-md">
          <div class="q-pa-md">
            <q-card class="my-card q-pa-sm" style="height:300px;">
              <q-card-section>
                <div style="height:40px">
                  <i class="fa-solid fa-circle-dot fa-2xl" style="color:#0358EE;"></i>
                </div>
                <div>
                  <p class="text-h5 text-weight-bold">Enterprise</p>
                </div>
                <div>
                  <p>Enjoy all features without limitations and boost up your sales.</p>
                </div>
                <div>
                  <span class="price text-h4 text-weight-bold">$499.99</span>
                  <span>/year</span>
                </div>
                <div>
                  <p>2.9% + $0.30 per transaction</p>
                </div>
                <div>
                  <q-btn push color="primary" label="Try for free 14 days"/>
                </div>
              </q-card-section>
            </q-card>
          </div>
        </div>
      </div>

      <div class="row">
        <div class="q-pa-md col-12 col-md">
          <q-card class="my-card">
            <q-markup-table>
              <thead>
                <tr>
                  <th class="text-left">Planning Features</th>
                  <th class="text-right">
                    <i class="fa-solid fa-circle-dot" style="color:#F67402;"></i>
                    <span>Basic</span>
                  </th>
                  <th class="text-right">
                    <i class="fa-solid fa-circle-dot" style="color:#01EEBE;"></i>
                    <span>Pro</span>
                  </th>
                  <th class="text-right">
                    <i class="fa-solid fa-circle-dot" style="color:#0358EE;"></i>
                    <span>Enterprise</span>
                  </th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <td class="text-left">Audit logs</td>
                  <td class="text-right">
                    <i class="fa-solid fa-circle-check" style="color:#28CA85;"></i>
                  </td>
                  <td class="text-right">
                    <i class="fa-solid fa-circle-check" style="color:#28CA85;"></i>
                  </td>
                  <td class="text-right">
                    <i class="fa-solid fa-circle-check" style="color:#28CA85;"></i>
                  </td>
                </tr>
                <tr>
                  <td class="text-left">Admin tools</td>
                  <td class="text-right">
                    <i class="fa-solid fa-circle-check" style="color:#28CA85;"></i>
                  </td>
                  <td class="text-right">
                    <i class="fa-solid fa-circle-check" style="color:#28CA85;"></i>
                  </td>
                  <td class="text-right">
                    <i class="fa-solid fa-circle-check" style="color:#28CA85;"></i>
                  </td>
                </tr>
                <tr>
                  <td class="text-left">Advanced reporting</td>
                  <td class="text-right">
                    <i class="fa-solid fa-circle-check" style="color:#28CA85;"></i>
                  </td>
                  <td class="text-right">
                    <i class="fa-solid fa-circle-check" style="color:#28CA85;"></i>
                  </td>
                  <td class="text-right">
                    <i class="fa-solid fa-circle-check" style="color:#28CA85;"></i>
                  </td>
                </tr>
                <tr>
                  <td class="text-left">Auto debit balance</td>
                  <td class="text-right">
                    <i class="fa-solid fa-circle-check" style="color:#A3A3A3;"></i>
                  </td>
                  <td class="text-right">
                    <i class="fa-solid fa-circle-check" style="color:#28CA85;"></i>
                  </td>
                  <td class="text-right">
                    <i class="fa-solid fa-circle-check" style="color:#28CA85;"></i>
                  </td>
                </tr>
                <tr>
                  <td class="text-left">Technical support</td>
                  <td class="text-right">
                    <i class="fa-solid fa-circle-check" style="color:#A3A3A3;"></i>
                  </td>
                  <td class="text-right">
                    <i class="fa-solid fa-circle-check" style="color:#28CA85;"></i>
                  </td>
                  <td class="text-right">
                    <i class="fa-solid fa-circle-check" style="color:#28CA85;"></i>
                  </td>
                </tr>
                <tr>
                  <td class="text-left">Professional maintenance</td>
                  <td class="text-right">
                    <i class="fa-solid fa-circle-check" style="color:#A3A3A3;"></i>
                  </td>
                  <td class="text-right">
                    <i class="fa-solid fa-circle-check" style="color:#A3A3A3;"></i>
                  </td>
                  <td class="text-right">
                    <i class="fa-solid fa-circle-check" style="color:#28CA85;"></i>
                  </td>
                </tr>
              </tbody>
            </q-markup-table>
          </q-card>
        </div>
      </div>
    </div>
  </q-page>
</template>

<script>
export default {
  name: 'PageIndex'
}
</script>
