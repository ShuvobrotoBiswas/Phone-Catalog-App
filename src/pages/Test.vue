  <template>
  <div class="q-pa-md">
    <q-header elevated>
        <q-toolbar>
    <q-toolbar-title>
    Phone Catalog App
          </q-toolbar-title>

    <div class="q-gutter-md row items-center">

      <q-btn  label="Click me">
        <q-menu :style="{ backgroundColor: '#eee', color: 'blue'}">
          <q-list dense style="min-width: 100px">
            <q-item clickable v-close-popup>
              <q-item-section>Products</q-item-section>
            </q-item>
            <q-separator />
            <q-item clickable>
              <q-item-section>Category</q-item-section>
              <q-item-section side>
                <q-icon name="keyboard_arrow_left" />
              </q-item-section>

              <q-menu auto-close anchor="top end" self="top start">
                <q-list>
                  <q-item
                    v-for="n in 1"
                    :key="n"
                    dense
                    clickable
                  >
                    <q-item-section>Smartphone</q-item-section>
                    <q-item-section side>
                      <q-icon name="keyboard_arrow_left" />
                    </q-item-section>
                    <!-- <q-menu auto-close anchor="top end" self="top start">
                      <q-list>
                        <q-item
                          v-for="n in 1"
                          :key="n"
                          dense
                          clickable
                        >
                          <q-item-section>IPhones</q-item-section>
                        </q-item>
                      </q-list>
                    </q-menu> -->
                  </q-item>
                </q-list>
              </q-menu>

            </q-item>
            <q-separator />
            <q-item clickable v-close-popup>
              <q-item-section>Quit</q-item-section>
            </q-item>
          </q-list>
        </q-menu>
      </q-btn>


    </div>
    </q-toolbar>
    </q-header>
  </div>
</template>

<script>
export default {
  // name: 'PageName',
}
</script>
