<template>
  <section class="c-profil">
    <div class="c-head">
      <div class="c-head__body">
        <el-row type="flex" justify="center">
          <el-col :xs="24" :sm="24" :md="20">
            <h2 class="title">Visi & Misi</h2>
            <h6 class="subtitle">RSUD Labuang Baji Makassar</h6>
          </el-col>
        </el-row>
      </div>
    </div>

    <el-row type="flex" justify="center">
      <el-col :xs="24" :sm="24" :md="20">
        <div class="c-breadcrumb">
          <el-breadcrumb separator-class="el-icon-arrow-right">
            <el-breadcrumb-item :to="{ path: '/' }">beranda</el-breadcrumb-item>
            <el-breadcrumb-item>profil</el-breadcrumb-item>
            <el-breadcrumb-item>visi & misi</el-breadcrumb-item>
          </el-breadcrumb>
        </div>

        <div class="c-profil--body">
          <el-card shadow="never">
            <h2 class="title">Visi</h2>
            <p>
              Visi RSUD Labuang Baji Makassar yaitu menjadi <strong>“rumah sakit
              unggulan di Sulawesi Selatan”</strong>
            </p>
          </el-card>

          <el-card shadow="never">
            <h2 class="title">Misi</h2>
            <ol>
              <li> 1. Mewujudkan profesionalisme SDM </li>
              <li> 2. Meningkatkan sarana dan prasarana rumah sakit </li>
              <li> 3. Memberikan pelayanan prima </li>
              <li> 4. Efisiensi biaya rumah sakit </li>
              <li> 5. Meningkatkan kesejahteraan karyawan </li>
            </ol>
          </el-card>
        </div>
      </el-col>
    </el-row>
  </section>
</template>

<script>
  export default {
    name: "visimisi"
  }
</script>
