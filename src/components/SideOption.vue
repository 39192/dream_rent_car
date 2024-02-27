<script>

</script>

<template>
    <div class="container">

        <div class="row">

            <div class="col-lg-3">

                <br>
                <div class="list-group">
                    <div class="list-group-item">
                        <h6>픽업일자</h6>
                        <div class="input-group date pickup-date">
                            <input class="form-control input-group-addon" id="pickup-date" readonly="">
                        </div>
                    </div>
                    <div class="list-group-item">
                        <h6>픽업시간</h6>
                        <select class="form-control" id="pickup-time">
                            <option value="08:00">08:00</option><option value="08:30">08:30</option><option value="09:00">09:00</option><option value="09:30">09:30</option><option value="10:00" selected="">10:00</option><option value="10:30">10:30</option><option value="11:00">11:00</option><option value="11:30">11:30</option><option value="12:00">12:00</option><option value="12:30">12:30</option><option value="13:00">13:00</option><option value="13:30">13:30</option><option value="14:00">14:00</option><option value="14:30">14:30</option><option value="15:00">15:00</option><option value="15:30">15:30</option><option value="16:00">16:00</option><option value="16:30">16:30</option><option value="17:00">17:00</option><option value="17:30">17:30</option><option value="18:00">18:00</option><option value="18:30">18:30</option></select>
                    </div>
                    <div class="list-group-item">
                        <h6>반납일자</h6>
                        <div class="input-group date return-date">
                            <input class="form-control input-group-addon" id="return-date" readonly="">
                        </div>
                    </div>
                    <div class="list-group-item">
                        <h6>반납시간</h6>
                        <select class="form-control" id="return-time">
                            <option value="00:00">00:00</option><option value="00:30">00:30</option><option value="01:00">01:00</option><option value="01:30">01:30</option><option value="02:00">02:00</option><option value="02:30">02:30</option><option value="08:00">08:00</option><option value="08:30">08:30</option><option value="09:00">09:00</option><option value="09:30">09:30</option><option value="10:00" selected="">10:00</option><option value="10:30">10:30</option><option value="11:00">11:00</option><option value="11:30">11:30</option><option value="12:00">12:00</option><option value="12:30">12:30</option><option value="13:00">13:00</option><option value="13:30">13:30</option><option value="14:00">14:00</option><option value="14:30">14:30</option><option value="15:00">15:00</option><option value="15:30">15:30</option><option value="16:00">16:00</option><option value="16:30">16:30</option><option value="17:00">17:00</option><option value="17:30">17:30</option><option value="18:00">18:00</option><option value="18:30">18:30</option><option value="19:00">19:00</option><option value="19:30">19:30</option><option value="20:00">20:00</option><option value="20:30">20:30</option><option value="21:00">21:00</option><option value="21:30">21:30</option><option value="22:00">22:00</option><option value="22:30">22:30</option><option value="23:00">23:00</option><option value="23:30">23:30</option></select>
                    </div>
                    <div class="list-group-item" style="background-color: #F5F5F5">
                        <div>렌트기간</div>
                        <div align="center">
                            <b id="rentDays" style="font-size: 18px; text-align: right;">1 일</b>
                        </div>
                    </div>
                </div>
                <br>
            </div>
            <!-- /.col-lg-3 -->

            <div class="col-lg-9">
                <br>

                <div class="info-sentence">
                    * 견적계산기는 렌트 비용 참고용입니다.
                </div>
                <div class="info-sentence">
                    * 자세한 내용은 <b><a href="https://cafe.naver.com/guamfree/2593378" style="color: rgb(107, 144, 220)" target="_blank"><u>드림렌트카 예약안내</u></a></b> 에서 확인해주세요.
                </div>
                <div class="info-sentence">
                    * 렌트기간 7일, 30일 이상의 장기 렌트일 경우 메일로 별도 문의 바랍니다. &lt; <b><a href="mailto:tillpark3@naver.com" style="color: rgb(107, 144, 220)" target="_blank"><u>tillpark3@naver.com</u></a></b> &gt;
                </div>

                <br>

                <!-- 컴팩트 (5인) -->
                <hr>
                <h4 class="title-car">컴팩트 (5인)&nbsp;&nbsp;<small>미츠비, 미라지</small></h4>
                <h6 class="title-rate">카페요금</h6>
                <table class="table table-bordered">
                    <thead>
                    <tr>
                        <th class="vertical-align-middle" style="width:50%;" colspan="2">
                            기본요금
                        </th>
                        <th style="width:50%" colspan="2">기본요금 + 추가보험(ZDC)</th>
                    </tr>
                    </thead>
                    <tbody>
                    <tr>
                        <td colspan="2">
                            <div id="compact-basic-below-three-days">$55.0</div>
                        </td>
                        <td id="compact-zdc-td" colspan="2">
                            <div id="compact-zdc-below-three-days">$65.0</div>
                        </td>
                    </tr>
                    <tr>
                        <th>예약금액</th>
                        <th>현장지불</th>
                        <th>예약금액</th>
                        <th>현장지불</th>
                    </tr>
                    <tr>
                        <td id="compact-basic-reservation">$10.0</td>
                        <td id="compact-basic-office">$45.0</td>
                        <td id="compact-zdc-reservation">$10.0</td>
                        <td id="compact-zdc-office">$55.0</td>
                    </tr>
                    </tbody>
                </table>
                <br>

                <!-- 미드사이즈 (5인) -->
                <hr>
                <h4 class="title-car">미드사이즈 (5인)&nbsp;&nbsp;<small>마즈다3, 엘란트라</small></h4>
                <h6 class="title-rate">카페요금</h6>
                <table class="table table-bordered">
                    <thead>
                    <tr>
                        <th style="width:50%" colspan="2">기본요금</th>
                        <th style="width:50%" colspan="2">기본요금 + 추가보험(ZDC)</th>
                    </tr>
                    </thead>
                    <tbody>
                    <tr>
                        <td colspan="2">
                            <div id="midSize2-basic-below-three-days">$65.0</div>
                        </td>
                        <td id="midSize2-zdc-td" colspan="2">
                            <div id="midSize2-zdc-below-three-days">$75.0</div>
                        </td>
                    </tr>
                    <tr>
                        <th>예약금액</th>
                        <th>현장지불</th>
                        <th>예약금액</th>
                        <th>현장지불</th>
                    </tr>
                    <tr>
                        <td id="midSize2-basic-reservation">$10.0</td>
                        <td id="midSize2-basic-office">$55.0</td>
                        <td id="midSize2-zdc-reservation">$10.0</td>
                        <td id="midSize2-zdc-office">$65.0</td>
                    </tr>
                    </tbody>
                </table>
                <br>

                <!-- 풀사이즈 (5인) -->
                <hr>
                <h4 class="title-car">풀사이즈 (5인)&nbsp;&nbsp;<small>마즈다6</small></h4>
                <h6 class="title-rate">카페요금</h6>
                <table class="table table-bordered">
                    <thead>
                    <tr>
                        <th style="width:50%" colspan="2">기본요금</th>
                        <th style="width:50%" colspan="2">기본요금 + 추가보험(ZDC)</th>
                    </tr>
                    </thead>
                    <tbody>
                    <tr>
                        <td colspan="2">
                            <div id="fullSize-basic-below-three-days">$75.0</div>
                        </td>
                        <td id="fullSize-zdc-td" colspan="2">
                            <div id="fullSize-zdc-below-three-days">$90.0</div>
                        </td>
                    </tr>
                    <tr>
                        <th>예약금액</th>
                        <th>현장지불</th>
                        <th>예약금액</th>
                        <th>현장지불</th>
                    </tr>
                    <tr>
                        <td id="fullSize-basic-reservation">$10.0</td>
                        <td id="fullSize-basic-office">$65.0</td>
                        <td id="fullSize-zdc-reservation">$10.0</td>
                        <td id="fullSize-zdc-office">$80.0</td>
                    </tr>
                    </tbody>
                </table>
                <br>

                <!-- SUV (5인) -->
                <hr>
                <h4 class="title-car">SUV (5인)&nbsp;&nbsp;<small>마즈다 CX5</small></h4>
                <h6 class="title-rate">카페요금</h6>
                <table class="table table-bordered">
                    <thead>
                    <tr>
                        <th style="width:50%" colspan="2">기본요금</th>
                        <th style="width:50%" colspan="2">기본요금 + 추가보험(ZDC)</th>
                    </tr>
                    </thead>
                    <tbody>
                    <tr>
                        <td colspan="2">
                            <div id="suv-basic-below-three-days">$80.0</div>
                        </td>
                        <td id="suv-zdc-td" colspan="2">
                            <div id="suv-zdc-below-three-days">$95.0</div>
                        </td>
                    </tr>
                    <tr>
                        <th>예약금액</th>
                        <th>현장지불</th>
                        <th>예약금액</th>
                        <th>현장지불</th>
                    </tr>
                    <tr>
                        <td id="suv-basic-reservation">$10.0</td>
                        <td id="suv-basic-office">$70.0</td>
                        <td id="suv-zdc-reservation">$10.0</td>
                        <td id="suv-zdc-office">$85.0</td>
                    </tr>
                    </tbody>
                </table>
                <br>

                <!-- 컨버터블 -->
                <hr>
                <h4 class="title-car">컨버터블&nbsp;&nbsp;<small>포드 머스탱</small></h4>
                <h6 class="title-rate">카페요금</h6>
                <table class="table table-bordered">
                    <thead>
                    <tr>
                        <th style="width:50%" colspan="2">기본요금</th>
                        <th style="width:50%" colspan="2">기본요금 + 추가보험(ZDC)</th>
                    </tr>
                    </thead>
                    <tbody>
                    <tr>
                        <td colspan="2">
                            <div id="convertible-basic-below-three-days">$120.0</div>
                        </td>
                        <td id="convertible-zdc-td" colspan="2">
                            <div id="convertible-zdc-below-three-days">$140.0</div>
                        </td>
                    </tr>
                    <tr>
                        <th>예약금액</th>
                        <th>현장지불</th>
                        <th>예약금액</th>
                        <th>현장지불</th>
                    </tr>
                    <tr>
                        <td id="convertible-basic-reservation">$10.0</td>
                        <td id="convertible-basic-office">$110.0</td>
                        <td id="convertible-zdc-reservation">$10.0</td>
                        <td id="convertible-zdc-office">$130.0</td>
                    </tr>
                    </tbody>
                </table>
                <br>

                <!-- 7인승 밴 (5인) -->
                <hr>
                <h4 class="title-car">7인승 밴&nbsp;&nbsp;<small>기아 세도나</small></h4>
                <h6 class="title-rate">카페요금</h6>
                <table class="table table-bordered">
                    <thead>
                    <tr>
                        <th style="width:50%" colspan="2">기본요금</th>
                        <th style="width:50%" colspan="2">기본요금 + 추가보험(ZDC)</th>
                    </tr>
                    </thead>
                    <tbody>
                    <tr>
                        <td colspan="2">
                            <div id="sevenVan-basic-below-three-days">$120.0</div>
                        </td>
                        <td id="sevenVan-zdc-td" colspan="2">
                            <div id="sevenVan-zdc-below-three-days">$140.0</div>
                        </td>
                    </tr>
                    <tr>
                        <th>예약금액</th>
                        <th>현장지불</th>
                        <th>예약금액</th>
                        <th>현장지불</th>
                    </tr>
                    <tr>
                        <td id="sevenVan-basic-reservation">$10.0</td>
                        <td id="sevenVan-basic-office">$110.0</td>
                        <td id="sevenVan-zdc-reservation">$10.0</td>
                        <td id="sevenVan-zdc-office">$130.0</td>
                    </tr>
                    </tbody>
                </table>
                <br>

                <!-- 8인승 밴 (5인) -->
                <hr>
                <h4 class="title-car">8인승 밴&nbsp;&nbsp;<small>오딧세이, 시에나</small></h4>
                <h6 class="title-rate">카페요금</h6>
                <table class="table table-bordered">
                    <thead>
                    <tr>
                        <th style="width:50%" colspan="2">기본요금</th>
                        <th style="width:50%" colspan="2">기본요금 + 추가보험(ZDC)</th>
                    </tr>
                    </thead>
                    <tbody>
                    <tr>
                        <td colspan="2">
                            <div id="eightVan-basic-below-three-days">$120.0</div>
                        </td>
                        <td id="eightVan-zdc-td" colspan="2">
                            <div id="eightVan-zdc-below-three-days">$140.0</div>
                        </td>
                    </tr>
                    <tr>
                        <th>예약금액</th>
                        <th>현장지불</th>
                        <th>예약금액</th>
                        <th>현장지불</th>
                    </tr>
                    <tr>
                        <td id="eightVan-basic-reservation">$10.0</td>
                        <td id="eightVan-basic-office">$110.0</td>
                        <td id="eightVan-zdc-reservation">$10.0</td>
                        <td id="eightVan-zdc-office">$130.0</td>
                    </tr>
                    </tbody>
                </table>
                <br>

                <br><br><br>

                <!-- /.row -->

            </div>
            <!-- /.col-lg-9 -->

        </div>
        <!-- /.row -->

    </div>
</template>

<style scoped>

</style>
